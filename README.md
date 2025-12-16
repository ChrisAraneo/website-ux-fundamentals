# Website UX Fundamentals

# Responsive design

![Responsive design](/images/responsive-design.png)

## What is responsive design?

Responsive web design allows a website to automatically adapt its appearance based on the device's screen size. This involves more than just resizing-elements. May change position and organization to optimize the user experience across different devices.

## Why responsive design matters?

1. **Market demand**
   - 74% of US adults own a desktop or laptop computer
   - 81% of US adults own a smartphone
   - Users expect consistent functionality across all devices
   - 185+ million active websites on the internet (2019)
   - New websites created every second
   - High demand for multi-device compatible designs
2. **UX designer job market**
   - 90% of UX designers work on websites or web-based applications
   - 76% work on mobile apps
   - WResponsive web design skills make portfolios more attractive to employers
3. **Easy screen adaptation**
   - Layouts adapt seamlessly to any screen size
   - Increases usability across all devices
   - Creates consistent good user experience
4. **Time and cost efficiency**
   - No need to design separate websites for every device size
   - Single responsive design serves all platforms
   - Reduces development and maintenance costs

## Native mobile apps & responsive web apps

Both approaches have their place in UX design. Understanding the trade-offs helps designers choose the right solution based on user needs, project constraints, and business goals.

### Dedicated mobile apps

**Native mobile app** is an app downloaded to device, accessed via home screen icon.

**Advantages**:
- Works offline after download/installation
- Integrates with device features (camera, microphone, location services)
- More design freedom (gestures, animations)
- Enhanced personalization options

**Disadvantages**:
- More expensive to build
- Requires separate versions for iOS and Android
- Must go through app store approval process
- Takes up device storage space
- Challenging for devices with limited storage

### Responsive Web Apps

**Responsive web app** is a website accessed through mobile browser and it adapts to device.

**Advantages**:
- Faster and cheaper to build
- No download required-saves device storage
- Accessible without app store
- Content viewable on all devices
- Saves time, resources, and money

**Disadvantages**:
- Requires internet connection or cell signal (no offline access)
- Harder for users to discover (not in app stores)
- Challenging to maintain across all screen sizes
- May be difficult to access for users in remote areas

## Responsive design mistakes

- Buttons that can't be seen
- Graphics that go off the side of the screen
- Content cut off or inaccessible
- Poor usability on certain devices

Example of bad UX is an image showing content extending beyond screen boundaries, causing usability issues.

## Breakpoints

**Breakpoints** are visual limits that determine when a responsive layout should change to fit all elements and components properly.

Live example:
- Adjust shape of browser window on computer to vertical rectangle
- Website will eventually **shift to mobile version** of site
- Transition happens automatically at breakpoint
- Triggered by code behind the website

With breakpoints you **don't** have to create a different design for every potential device and screen size. You design for a **few key sizes**.

## Above the fold

**"Above the fold"** is content on webpage that doesn't require scrolling to experience.

## Critical design questions

When plotting different screen sizes, ask:

1. **Element location**
   - Do elements on the page need to move location?
   - Which parts need to stay **above the fold** on smaller screens?
   - Which can move **below the fold**?
2. **Image scaling**
   - How do images need to be scaled?
   - Are there certain images (like **hero images**) that need to remain large across all screen sizes?
   - What's the minimum acceptable size for each image type?
3. **Navigation adjustments**
   - How will navigation elements adjust as screen size changes?
   - Example: Moving from **top navigation bar** to **hamburger menu**
   - What interactive elements need to change format?

# Information architecture

![Information architecture](/images/information-architecture.png)

## What is information architecture (IA)?

Information architecture (IA) organizes content to help users understand where they are in a product and where the information they want is. It serves as the roadmap for users to navigate and find everything they need from your website.

Information architecture is fundamentally about organizing content for excellent user flow. To create effective IA, designers must thoroughly understand their users' goals, behaviors, and expectations.

## Key foundation for IA

Effective information architecture should be informed by:

- **User research** - Understanding user goals, behaviors, and expectations
- **Competitive audits** - Examining how existing products are structured
- **User knowledge** - Deep understanding of who you're designing for

## Why information architecture matters?

1. **Organizes and defines website structure**
   - Creates easy navigation for users
   - Establishes clear organizational patterns
2. **Provides high-level product view**
   - Shows how website elements fit together
   - Clarifies relationships between different parts
   - Improves overall design process
3. **Facilitates stakeholder review**
   - Enables stakeholders to evaluate content appropriateness
   - Helps assess if content placement aligns with business goals
   - Supports product goal achievement
4. **Supports engineering development**
   - Helps engineers understand data organization
   - Ensures development matches visual designs
   - Makes colleagues' jobs easier
5. **Saves development time**
   - Prevents messy architecture that delays web development
   - Reduces costly mistakes and rework
6. **Enables design iteration**
   - Allows ideas to grow and evolve
   - Supports adaptation at different project stages
   - Key skill for UX designers

# Common website structures

![Common website structures](/images/common-website-structures.png)

## Common website structures

### 1. **Hierarchical model** (most popular)

- **Structure**: Top-down approach with parent and child levels, similar to a family tree
- **Components**:
  - Homepage at the top
  - Parent pages (main categories) in navigation bar
  - Child pages (subcategories) under each parent
- **Example**: HBO.com with main categories (Series, Movies, Docs) and subcategories (Featured Series, Specials, Sports)
- **Key concept**: Organizes content by importance-what's most/least important and how content connects

### 2. **Sequential model**

- **Structure**: Leads users through step-by-step linear process
- **Navigation**: Users move from starting page to endpoint in order
- **Limitations**: Cannot skip pages or navigate out of order in true sequential structures
- **Example**: Car insurance quote forms, online surveys
- **Purpose**: Move users toward an end goal through sequential steps

### 3. **Matrix model** (Web Model)

- **Structure**: Content linked in multiple ways, allowing users to follow their own path
- **Navigation**: Users can access any page while still reaching all other pages
- **Features**: Free exploration with interconnected content
- **Example**: News websites with navigation menus, featured content, and hyperlinked related articles
- **Caution**: Considered outdated by some UX designers; can be difficult to navigate without clear direction
- **Use Case**: Websites wanting users to interact with lots of content rather than following a specific journey

### 4. **Database model**

- **Structure**: Combines organized information database with search functionality
- **Features**: Advanced filtering and search capabilities
- **Dynamic Experience**: Content categorized with tags for easy searching
- **Examples**: Social media networks (location tags), Google Maps (searchable addresses and categories)

## Advantages of using common website structures

Common website structures help users browse more efficiently by providing familiar information architecture patterns. Understanding the four common website structures is essential for organizing content effectively and building information architecture that meets user needs.

- **Meets User Expectations**: Users have prior experience with these structures across different websites
- **Improves Navigation**: Adds organization and logical cues to orient and direct users
- **Proven Effectiveness**: Tested over time and evolved based on user and designer feedback
- **Efficient Development**: Saves time by providing starting frameworks rather than building from scratch

## Choosing the right structure

- Depends on website and user needs
- Most websites use **combinations** of multiple structures
- Flexibility to blend structures for specific project requirements
- Can go beyond these models for unique brand requirements
- **Critical**: Users must be able to easily and effectively navigate the website

# Sitemaps

![Sitemaps](/images/sitemaps.png)

## Sitemap

A **sitemap** is a diagram showing how pages are prioritized, linked, and labeled in a website or app.

Sitemaps are essential tools for planning website architecture and ensuring all users can successfully navigate the design. Clear organizational structure through sitemaps is essential for user navigation and successful website design. Sitemaps serve as foundational planning tools for web architecture.

## Benefits of using sitemaps

1. **Clear organizational path**: Helps visualize site structure in early planning stages
2. **Identifies connectivity needs**: Shows which areas require elaborate connections
3. **Comprehensive overview**: See all pages in the order they appear to users
4. **Catch mistakes early**: Spot forgotten pages or opportunities to condense content
5. **Search engine indexing**: Helps Google and other search engines understand site content
6. **Accessibility**: Creates organized flow for all users, especially those using assistive technology

## Sitemap Structure (hierarchical example)

- **Top rectangle**: Homepage (user entry point)
- **Row of rectangles below**: Main categories connected to homepage
- **Columns below categories**: Subcategories for each main category

## Building a sitemap

### Step 1: Identify common pages
- Think about standard website pages (homepage, product pages, shopping cart, etc.)
- Review competitive audit findings
- Note common pages from competitor websites
- Example: Library websites typically have search results pages

### Step 2: Recall user research
- Reference empathy maps, personas, user stories, and user journey maps
- Focus on user problems and goals
- Map user journey to sitemap structure
- Example: Shane's journey-browse books → choose book → reserve → waitlist → pick up

### Step 3: Choose website structure
- Select from: hierarchical, sequential, matrix, or database
- Can use combination of structures
- Example: Library website uses hierarchical structure (homepage with connected pages)
- **Pro Tip**: Use templates based on common structures to jumpstart process

### Step 4: Start with homepage
- Homepage is the access point and first user experience
- Place at top of sitemap diagram

### Step 5: Define main categories
- Add to row of rectangles connected to homepage
- These appear in navigation bar on actual website
- Example for library website: Books, Checkout Cart, User Account, About
- Note: Number of categories varies by project needs

### Step 6: Add subcategories (child pages)
- Fill rectangles below each main category
- Example for Books category: Recent Releases, Most Popular, Recommendations
- Continue for all main categories

## Example sitemap

![Example of a visual sitemap for a website that sells coffee products](https://api.backlinko.com/app/uploads/2025/05/sitemap-1280x1054.webp)

(source: [https://backlinko.com/sitemap-examples](https://backlinko.com/sitemap-examples))

## Sitemap types by website size

- **Flat sitemaps**: Small websites (under 100 pages) with maximum 4 vertical levels
- **Deep sitemaps**: Large websites (1,000+ pages) with 5 or more vertical levels

# Homepage layouts

![Homepage layouts](/images/homepage-layouts.png)

## Homepage layouts

Homepages serve as the entry point and central navigation hub for websites. Proper layout organization guides users and helps them find information quickly.

Always select the layout that best serves your users and project goals rather than following current trends. The UX design industry constantly evolves, and what's trending may not reflect optimal usability or accessibility.

# Common homepage layouts

## 1. Single-column

- **Structure**: One vertical column for content
- **Characteristics**: Simplest layout option with logical top-to-bottom stacking (navigation → content → footer)
- **Best for**: Mobile websites, reading-focused content, emphasizing one main element
- **Advantage**: Easy scrolling and focus on text

## 2. Multicolumn

- **Structure**: Two or more columns for content
- **Key element**: Clear **focal point** (specific area capturing user attention)
- **Content distribution**: Supporting content occupies 25-45% of page
- **Design principle**: Uses visual weight and hierarchy
- **Common use**: Desktop websites, above-the-fold content display
- **Pro tip**: One column often reserved for ad space

## 3. Box

- **Structure**: Boxes/squares of varying sizes and proportions
- **Visual equality**: Same-sized, evenly-spaced boxes = equal importance
- **Emphasis technique**: Larger or separated boxes draw attention
- **Common applications**: E-commerce homepages (e.g., Amazon), UX portfolios, seasonal content rotation
- **Advantage**: Easy content swapping

## 4. Featured image (Single image)

- **Structure**: Single dominant image/video occupying entire page
- **Purpose**: Create strong first impression and emotional connection
- **Requirements**: High-quality, message-relevant imagery
- **Navigation**: Often includes sticky/fixed menu bar
- **Best for**: Product pages, brand storytelling

## 5. Asymmetrical

Purposefully imbalanced designs emphasizing specific elements through natural eye-tracking patterns:

### **F-Shape Eye-Tracking Pattern**

- **User behavior**: Browse content following F-shape
- **Best for**: Text-heavy pages, search results
- **Design priority**: Most important information at top
- **User tendency**: Won't read to bottom

### **Z-Shape Eye-Tracking Pattern**

- **User behavior**: Left to right → diagonal left → right again
- **Natural pattern**: Mimics Western left-to-right, top-to-bottom reading
- **Best for**: Sites with less content
- **Accessibility note**: Users with visual impairments follow same patterns with assistive technology

## 6. Grid of Cards

- **Structure**: Series of uniform-sized rectangular cards previewing content
- **Distinction from box layout**: Cards are interrelated within same list (vs. independent boxes)
- **Technical features**: Card/list view switching, lazy loading
- **Responsive design**: Card size adapts to screen size
- **Common applications**: Recipe blogs, streaming services (YouTube, Pinterest, TED)

## 7. Tiered Layer Cake

- **Structure**: Stacked horizontal rows with varying column counts per layer
- **Flexibility**: Inconsistent column numbers across layers
- **Responsive design advantage**: Layers easily rearranged or swapped for different screen sizes
- **Distinction**: No all-encompassing container or long sidebars (unlike multicolumn)
- **Desktop to mobile**: Multiple columns collapse to single column

## Takeways

1. **Simplicity vs. Complexity:** Choose layout complexity based on content needs and screen size
2. **Responsive Design:** Different layouts may be appropriate for different device sizes (single-column for mobile, multicolumn for desktop)
3. **Visual Hierarchy:** All layouts should consider hierarchy, color, and variety in element organization
4. **Focal Points:** Multicolumn and featured image layouts particularly benefit from clear focal points
5. **Purpose-Driven Design:** Each layout serves specific purposes:
   - Single-column: Reading and simplicity
   - Multicolumn: Content variety and desktop optimization
   - Box: Organization and categorization
   - Featured image: Impact and emotion
6. **Quality Matters:** Especially for featured image layouts, high-quality visuals are essential
7. **Navigation Consistency:** Fixed/sticky navigation bars help maintain user orientation

## UX considerations

- Consider target devices and screen sizes
- Match layout to content type and user goals
- Maintain consistency within chosen layout system
- Use established patterns users are familiar with
- Prioritize visual quality, especially for image-heavy layouts
- Balance aesthetics with functionality
- Test layouts with actual users to validate effectiveness

# Wireframes

![Wireframes](/images/wireframes.png)

## What is wireframe?

A **wireframe** is an outline or sketch of a product/screen consisting of shapes, lines and minimal text.
Wireframes help designers figure out the layout of the page. They act like blueprints for site structure.

## Wireframing conventions

- **Text** is represented by horizontal lines
- **Icons/Images** are represented by squares with X overlay
- **Call-to-action buttons (CTA)** are rectangles or circles
- **Placeholders** are represented by shapes or lines holding space for future visual elements

## Paper and digital wireframes

Many UX designers start with paper wireframes and later switch to digital to balance speed of exploration with refinement.

### Paper wireframing

- Start sketching on paper
- Allows working through many iterations faster
- Easy to throw away wireframes that aren't working
- Typical starting point for many UX designers

### Grid paper

- Helps maintain proportions
- Assists with alignment
- Provides consistent scaling
- Makes comparison easier across versions

### Digital wireframing

- Create wireframes using digital tools
- Switch to digital after paper exploration

## Responsive design wireframes

Implement layout changes based on device/screen size to improve user experience and accessibility across devices. Best practice is to create at least 5 versions of every important page.

### Design strategy: largest to smallest

- Assume the desktop homepage wireframe is the **largest screen** to design for
- Create progressively smaller versions by asking:
  - "What would a medium version look like?"
  - "What would a small version look like?"
  - "Which components will be **removed**?"
  - "Which will **stay**?"
  - "Which will **shift position** or **change format**?"

### Mobile wireframe

- Draw smaller, portrait-oriented outline (narrower than desktop)
- Use grid lines as placement guide
- Scale desktop elements down (~1/3 size for mobile)
- May span multiple A5 pages when sketching

### Tablet wireframe

- Draw outline larger than mobile, smaller than desktop
- Still portrait-oriented
- Scale elements proportionally using grid

## Usability, accessibility and visual clutter

When adapting for responsive layouts, verify:

- **Did I think about usability** when designing for smaller screen sizes?
- **Did I consider accessibility** when designing for new screen sizes?
- **Did I try to reduce clutter** and save space when designing for new screen sizes?

### Design considerations for smaller screens

- **Remove** non-essential UI components
- **Maintain** critical elements
- **Shift** positions or change formats
- **Space-saving elements**: Hamburger menus, cards, carousels
- **Reduce clutter**: Prioritize usability and accessibility

## Sketching paper wireframes

### Preparation

1. **List required information**: document all elements needed on page (navigation, images, text descriptions)
2. **Reference sitemap**: use sitemap to determine page structure and element prioritization
3. **Gather materials**: grid paper (or template), pen/pencil

### Drawing process

1. **Create multiple variations**: sketch 4-5 different layout versionss. Each version should have different design solutions.
2. **Consider all device types**: sketch wireframes for each device type and screen size.
3. **Top-to-bottom approach**: it is recommended to use *top-to-bottom* design approach. That is how users experience webpage.

### Review and refinement

1. **Identify best elements**: Mark favorite features from each wireframe
2. **Combine marked elements**: Create final wireframe integrating best components
3. **Repeat for all pages**: Apply same process to remaining website pages

### Documentation

1. **Note design decisions**: note reasoning behind breakpoint decisions, element positions on different devices
2. **Document wireframe progression for portfolio**
3. **Document takeaways**: write down what you have learned

## Above the fold

**"Above the fold"** is content on webpage that doesn't require scrolling to experience.

## Transition to digital versions

After completing paper wireframes for all screen sizes, transition to digital wireframing tools to refine designs and prepare for prototyping. At this point placeholders should be filled with images or components.

## Best practices

1. **Focus on structure, not aesthetics** - Detailed design comes later
2. **Iteration is essential**: Designs evolve throughout the process
3. **Grid paper benefits**: Enables consistent scaling and element proportion
4. **Industry standards**: Facilitate team communication and understanding
5. **Progressive refinement**: Paper sketches → digital wireframes
6. **Use standard visual conventions** - Improves communication with team members
7. **Always reference sitemap** - Ensures all required elements are included

# Example wireframe

![Example wireframe](/images/example-wireframe.png)

## Library homepage wireframe

This section covers creating an example wireframe for a library homepage.

## Header area (top of page)

1. **Logo** (upper left corner)
   - Add rectangle with word "logo"
   - Makes purpose clear to yourself and reviewers
2. **Navigation links** (next to logo)
   - Search
   - Discover
   - Donate
   - About pages
   - Important hyperlinks for specific website type
3. **Account & cart icons** (right side of header)
   - Common design pattern in left-to-right reading languages
   - Cart link typically furthest to the right
4. **Hero Image** (below header)
   - Takes up majority of header area (but not all)
   - Include text next to image to explain content
   - Could feature author or new book release
   - Draw X in boxes to indicate image placeholder

## Above the fold

In the "above the fold" area of the library homepage website wireframe:
- Add rectangles with X inside (image placeholders)
- Add lines for corresponding descriptions
- Show latest books
- Ensure users immediately notice content when landing on homepage

## Below the fold

Include additional content for variety:
- Create new section for more books
- List six books in two groups of three rectangles
- Add lines below each for:
  - Book title
  - Author name
  - Other relevant information

## Footer area

Typical footer content:
- Organization's social media pages
- Terms and conditions
- Career opportunities
- Privacy policy
- Other useful navigation links

Design approach:
- Add lines to indicate hyperlinks
- Include full version of logo with library name
- Use smaller logo version in header to save space

## Multiple homepage wireframe options

Best practice is to create around 5 versions of important pages like homepage.

**Option A:**
- Large hero image with text next to it
- Could introduce author or featured book collection

**Option B:**
- Really prominent search field in top right
- Hero image of library in background

**Option C:**
- Logo, search, and navigation grouped in one floating box
- Other images and text for books further down page

**Option D:**
- Simplified navigation
- Discover, about, and donate areas as parts of actual homepage

**Option E:**
- "Outside the box" approach
- Search super prominent (search engine style)

## Selection process

After creating multiple wireframes, identify features you like most by marking them with a star.
Once you've identified the best parts, combine them into one new wireframe.

## Takeaways

1. **Exploration is critical** - Create multiple versions to find the best solution
2. **Follow industry standards** - Use consistent visual conventions for clarity
3. **Plan before drawing** - List required elements upfront
4. **Think systematically** - Work through page sections logically (header → content → footer)
5. **Above the fold matters** - Place important content where users see it immediately
6. **Iterate and refine** - Identify best elements from multiple versions
7. **Be creative** - Don't be afraid to try unconventional layouts
8. **Combine strengths** - Final wireframe can merge best parts from all variations
9. **Wireframes are only blueprints**: They're meant to be rough, fast, and iterative. The goal is exploring ideas, not creating polished designs at this stage.

# Common website UI components

![Common website UI components](/images/common-website-components.png)

## Quick reference table

| Element | Description | Use Case |
|---------|-------------|----------|
| **Hamburger Menus** | Collapsible navigation with three-line icon. Hide full navigation lists behind a clickable icon, revealing them only when needed (vs. showing all navigation links at once) | Condenses navigation lists for small screens |
| **Cards** | Surfaces containing content about a single subject. Fit related information into compact, stackable units that can be arranged efficiently in vertical columns on narrow screens | Organizes information in scannable, stackable units |
| **Carousels** | Scrollable feeds of images or cards. Allow multiple images/items to occupy the same horizontal space by letting users swipe through them sequentially (vs. displaying all items side-by-side) | Displays multiple items in limited horizontal space |
| **CTA buttons** | Call-to-action buttons that prompt users to take specific actions. Feature prominent styling with action-oriented text (e.g., "Get Started", "Buy Now", "Sign Up") to drive conversions and guide users toward desired outcomes | Drives user actions and conversions with clear, visible prompts |

## Hamburger menu icon

### Purpose

The hamburger menu icon toggles hidden navigation menus, primarily for responsive web design. It saves screen space, maintains clean interfaces, and provides a universally recognized symbol for collapsed navigation on mobile and small screens.

### Visual characteristics

**Structure:**
- Three horizontal lines stacked vertically with equal spacing
- Uniform line thickness and equal length
- Minimal, unambiguous design
- Monochromatic, matching site color scheme
- Square aspect ratio (approximately 1:1)
- Typical size: 24x24px to 48x48px

**Variations:** Rounded ends, animated transformations to "X" or arrow when activated

### Functionality

**Primary interaction:**
- Tap/click opens hidden navigation menu
- Often transforms visually when active (e.g., rotates to "X")
- Triggers slide-out panel, dropdown, overlay, or full-screen navigation
- Second tap/click closes the menu

**Accessibility:**
- Include ARIA labels (`aria-label="Menu"` or `aria-label="Toggle navigation"`)
- Must be keyboard accessible (Tab + Enter/Space)
- Announce state changes to screen readers
- Minimum touch target: 44x44px

### Placement and usage

**Optimal placement:**
- **Mobile**: Top-left corner (most common) or top-right corner (RTL interfaces)
- **Desktop/Tablet**: Less common; used in header when full navigation doesn't fit
- **Fixed position**: Often remains visible while scrolling

**When to Use:**
- Mobile-first responsive websites
- Applications with extensive navigation options
- Interfaces prioritizing content over navigation

**Best practices:**
- Maintain consistent placement across pages
- Ensure sufficient color contrast (4.5:1 minimum)
- Consider pairing with "Menu" label for clarity
- Provide visual feedback on hover/tap
- Open menu quickly (< 300ms) with smooth animation

## Cards

### Purpose

Cards are container components that group related content and actions into digestible units. They organize information into scannable sections, provide clickable surfaces for navigation, and adapt responsively to different screen sizes.

Common uses: product listings, article previews, user profiles, dashboard widgets, and feature highlights.

### Visual characteristics

**Container:** Defined boundaries with white/light background, subtle drop shadows (1-8dp elevation), rounded corners (2-8px), internal padding (16-24px)

**Structure:** Header (title, icon), media area (image/video, optional), body content (text, data), footer (buttons, metadata)

**Typography:** Title (18-24px), body (14-16px), metadata (12-14px)

**States:** Default, hover (elevated shadow), active (scale reduction), focus (visible outline), disabled (reduced opacity)

### Functionality

**Interaction types:**
- **Clickable**: Entire card navigates to detail page
- **Action-based**: Multiple buttons for specific actions
- **Informational**: Display-only with possible interactive elements
- **Expandable**: Reveals additional content on interaction
- **Selectable**: Multi-select with checkboxes

**Features:** Dynamic updates, lazy loading, filtering/sorting, keyboard navigation, screen reader support, semantic HTML with ARIA labels, minimum touch targets (44x44px)

### Placement and usage

**Layout patterns:**
- **Grid**: Responsive columns (1 mobile, 2-3 tablet, 3-4 desktop) with 16-32px gaps
- **List/Feed**: Single column, full-width stacked vertically
- **Masonry**: Variable heights for dynamic layouts
- **Dashboard**: Mixed sizes (1x1, 2x1, 2x2) for metrics

**Best practices:**
- Keep content concise and scannable
- Use high-quality, optimized images
- Maintain consistent styling (padding, shadows, typography)
- Stack vertically on mobile with proper breakpoints
- Ensure 4.5:1 color contrast for accessibility

**When to use:**
Collections of similar content, browsable catalogs, content previews

**When to avoid:**
Simple lists, dense data tables, sequential forms, long-form reading content

**Common types:**
Product cards, article cards, profile cards, media cards, statistic cards, action cards

## Carousel

### Purpose

Carousels are interactive components that display multiple content items in a rotating slideshow format. They maximize screen space by showing one item at a time while allowing users to browse through a collection sequentially or automatically.

Common uses: featured content highlights, product showcases, image galleries, testimonials, and promotional banners.

### Visual characteristics

**Container:** Fixed-width/height viewport with overflow hidden, displaying one slide at a time

**Structure:** Content slides (images, text, or mixed), navigation arrows (left/right), indicator dots/thumbnails, optional auto-play controls

**Transitions:** Slide, fade, or custom animations (typically 300-600ms duration)

**States:** Active slide (fully visible), inactive slides (hidden or partially visible), hover (reveals controls), focus (keyboard navigation indicators)

### Functionality

**Navigation methods:**
- **Arrow buttons**: Previous/next controls on left/right edges
- **Indicator dots**: Clickable position markers below carousel
- **Touch gestures**: Swipe left/right on mobile devices
- **Keyboard**: Arrow keys for navigation, Tab for focus
- **Auto-play**: Automatic rotation with configurable interval (3-5 seconds typical)

**Features:** Infinite loop (cycles back to start), pause on hover/interaction, lazy loading for performance, responsive resizing, optional thumbnails preview

**Accessibility:** ARIA roles (`role="region"`, `aria-roledescription="carousel"`), keyboard navigation, pause controls, screen reader announcements for slide changes

### Placement and usage

**Layout patterns:**
- **Hero section**: Full-width at top of page for featured content
- **Product gallery**: Product detail pages with image carousel
- **Content showcase**: Homepage sections highlighting features or offerings
- **Testimonials**: Customer reviews or quotes rotation

**Best practices:**
- Limit to 3-7 slides for optimal engagement
- Use clear, visible navigation controls
- Provide pause/play controls for accessibility
- Ensure touch targets minimum 44x44px
- Include alternative navigation (not carousel-only)
- Avoid auto-play for text-heavy content

**When to use:**
Featured content rotation, image galleries, space-constrained showcases

**When to avoid:**
Critical information (may be missed), content requiring comparison, forms or interactive elements within slides, more than 7-10 slides

**Common types:**
Image carousel, content carousel, product carousel, testimonial carousel, banner carousel

## Call-to-action buttons

### Purpose

Call-to-action (CTA) buttons prompt users to take specific, desired actions that drive conversions and achieve business goals. They guide users through the customer journey by providing clear next steps and reducing decision paralysis.

Common uses: Sign-ups, purchases, downloads, subscriptions, form submissions, navigation to key pages, and lead generation.

### Visual characteristics

**Container:** Rectangular shape with rounded corners (4-8px), solid background color (high contrast with page), clear padding (12-16px vertical, 24-48px horizontal)

**Typography:** Bold or medium weight (500-700), larger than body text (16-18px minimum), sentence case or title case, action-oriented verbs

**Colors:** Primary brand color for main CTA, high contrast with background (4.5:1 minimum), secondary/tertiary CTAs use outline or muted colors

**States:** Default (solid color), hover (darker shade or elevation), active (pressed appearance), focus (visible outline), disabled (grayed out, reduced opacity)

### Functionality

**Primary actions:**
- **Submit forms**: Complete purchases, registrations, or data submissions
- **Navigate**: Direct users to landing pages, product details, or key sections
- **Download**: Trigger file downloads or app installations
- **Share/Save**: Enable social sharing or content bookmarking
- **Contact**: Open contact forms, chat, or email clients

**Interaction behavior:** Single click/tap triggers action, provides immediate feedback (loading states, confirmation messages), prevents double-submission, accessible via keyboard (Enter/Space)

**Features:** Clear action text (2-5 words), sense of urgency when appropriate ("Get Started Now", "Limited Offer"), tooltip on hover for additional context, icon support for visual reinforcement

### Placement and usage

**Strategic placement:**
- **Hero section**: Primary CTA above the fold for maximum visibility
- **End of content**: After value proposition or product description
- **Navigation bar**: Top-right corner for persistent access
- **Modals/Forms**: Bottom-right or centered for form submission
- **Cards**: Bottom or top-right within card boundaries

**Best practices:**
- One primary CTA per section to avoid confusion
- Use action verbs ("Buy", "Start", "Join", "Download", "Learn")
- Create visual hierarchy (size, color, position)
- Ensure minimum touch target size (44x44px)
- Place where users naturally look (F-pattern, Z-pattern)
- Test with A/B testing for optimal performance

**When to use:** Driving conversions, guiding user flow, highlighting primary actions, completing transactions

**When to avoid:** Overusing multiple CTAs that compete for attention, unclear value proposition, premature asks before establishing trust

**Common types:** Primary CTA (most important action), secondary CTA (alternative action), tertiary CTA (low-priority action), floating/sticky CTA (persistent visibility)

## Choosing components for your project

1. **Navigation Needs**
   - How many navigation items?
   - Will they fit horizontally on mobile?
   - Consider: Hamburger menu

2. **Content Volume**
   - Lots of similar items to display?
   - Need scannable organization?
   - Consider: Cards

3. **Visual Content**
   - Multiple images to showcase?
   - Limited screen space?
   - Consider: Carousel

4. **User Actions**
   - Key actions users should take?
   - Need to drive conversions?
   - Consider: CTA buttons

# Image attributions

- Responsive design
  - https://www.pexels.com/pl-pl/zdjecie/szary-telefon-obrotowy-209716/
  - https://www.pexels.com/pl-pl/zdjecie/staroswiecki-vintage-klasyczny-ekran-12752566/
- Information architecture
  - https://www.pexels.com/pl-pl/zdjecie/kolekcja-japonskich-plakatow-sciennych-w-stylu-vintage-35089102/
- Common website structures
  - https://www.pexels.com/pl-pl/zdjecie/symetryczna-perspektywa-stalowego-mostu-kolejowego-35064415/
- Sitemaps
  - https://www.pexels.com/pl-pl/zdjecie/edukacja-mapa-strony-widok-z-gory-15835241/
- Home layouts
  - https://www.pexels.com/pl-pl/zdjecie/krajobraz-domy-znane-miejsce-podroz-21631486/
- Wireframes
  - https://www.pexels.com/pl-pl/zdjecie/bialy-papier-do-drukarki-196645/
- Example wireframe
  - https://www.pexels.com/pl-pl/zdjecie/partie-ksiazek-na-drewnianej-polce-1565245/
- Common website UI components
  - https://www.pexels.com/pl-pl/zdjecie/burger-z-plasterkami-warzyw-z-bliska-fotografia-2702674/
