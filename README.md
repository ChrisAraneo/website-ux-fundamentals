# Website UX Fundamentals

# Responsive design

![Responsive design](/images/responsive-design.png)

## What is responsive design?

Responsive web design allows a website to automatically adapt its appearance based on the device's screen size. This involves more than just resizing-elements. Components may change position and organization to optimize the user experience across different devices.

## Why responsive design matters?

Responsive web design is important because most people use multiple devices (74% have computers, 81% have smartphones) and expect websites to work well on all of them. Since the vast majority of UX designers (90%) focus on web-based projects, mastering responsive design is crucial for professional growth in the industry. It also saves time and money because you only need to build one website that works on every device instead of making separate versions for each screen size.

## Native mobile apps & responsive web apps

Both approaches have their place in UX design. Understanding the trade-offs helps designers choose the right solution based on user needs, project constraints, and business goals.

### Native mobile apps

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

### Responsive web apps

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

**Above the fold** is content on webpage that doesn't require scrolling to experience.

## Critical design questions

When designing across different screen sizes, consider:

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

## Why information architecture matters?

Good information architecture creates clear navigation and shows how all website parts connect. It helps stakeholders review content and engineers understand how to build the site correctly. IA saves development time by preventing messy mistakes and allows designers to improve their ideas at different project stages.

## Key foundation for IA

Effective information architecture should be informed by:

- **User research** - understanding user goals, behaviors, and expectations
- **Competitive audits** - examining how existing products are structured
- **User knowledge** - deep understanding of who you're designing for

# Common website structures

![Common website structures](/images/common-website-structures.png)

## Common website structures

### 1. **Hierarchical model** (most popular)

***Top-down approach with parent and child levels, similar to a family tree.***

***Organizes content by importance-what's most/least important and how content connects.***

- Homepage at the top
- Parent pages (main categories) in navigation bar
- Child pages (subcategories) under each parent

**Example:**

HBO.com with main categories (Series, Movies, Docs) and subcategories (Featured Series, Specials, Sports)

### 2. **Sequential model**

***Leads users through step-by-step linear process.***

- **Navigation** - users move from starting page to endpoint in order
- **Limitations** - cannot skip pages or navigate out of order in true sequential structures
- **Purpose** - move users toward an end goal through sequential steps

**Example:**

Car insurance quote forms, online surveys.

### 3. **Matrix model** (Web model)

***Content linked in multiple ways, allowing users to follow their own path.***

- **Navigation** - users can access any page while still reaching all other pages
- **Features** - free exploration with interconnected content
- **Caution** - considered outdated by some UX designers; can be difficult to navigate without clear direction
- **Use case** - websites wanting users to interact with lots of content rather than following a specific journey

**Example:**

News websites with navigation menus, featured content, and hyperlinked related articles.

### 4. **Database model**

***Combines organized information database with search functionality.***

- **Features** - advanced filtering and search capabilities
- **Dynamic experience** - content categorized with tags for easy searching

**Example:**

Social media networks (location tags), Google Maps (searchable addresses and categories).

## Advantages of using common website structures

Common website structures help users browse more efficiently by providing familiar information architecture patterns. Understanding the four common website structures is essential for organizing content effectively and building information architecture that meets user needs.

- **Meets user expectations** - users have prior experience with these structures across different websites
- **Improves navigation** - adds organization and logical cues to orient and direct users
- **Proven effectiveness** - tested over time and evolved based on user and designer feedback
- **Efficient development** - saves time by providing starting frameworks rather than building from scratch

## Choosing the right structure

- Depends on website and user needs
- Most websites use **combinations** of multiple structures
- Flexibility to blend structures for specific project requirements
- Can go beyond these models for unique brand requirements
- **Users must be able to easily and effectively navigate the website**

# Sitemaps

![Sitemaps](/images/sitemaps.png)

## Sitemap

A **sitemap** is a diagram showing how pages are prioritized, linked, and labeled in a website or app.

Sitemaps are essential tools for planning website architecture and ensuring all users can successfully navigate the design. Clear organizational structure through sitemaps is essential for user navigation and successful website design. Sitemaps serve as foundational planning tools for web architecture.

## Benefits of using sitemaps

1. **Clear organizational path** - helps visualize site structure in early planning stages
2. **Identifies connectivity needs** - shows which areas require elaborate connections
3. **Comprehensive overview** - see all pages in the order they appear to users
4. **Catch mistakes early** - spot forgotten pages or opportunities to condense content
5. **Search engine indexing** - helps Google and other search engines understand site content
6. **Accessibility** - creates organized flow for all users, especially those using assistive technology

## Sitemap structure

- **Top rectangle** - homepage (user entry point)
- **Row of rectangles below** - main categories connected to homepage
- **Columns below categories** - subcategories for each main category

## Example sitemap

![Example of a visual sitemap for a website that sells coffee products](https://api.backlinko.com/app/uploads/2025/05/sitemap-1280x1054.webp)

(source: [https://backlinko.com/sitemap-examples](https://backlinko.com/sitemap-examples))

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
- **Pro Tip** - use templates based on common structures to jumpstart process

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

## Sitemap types by website size

- **Flat sitemaps** - small websites (under 100 pages) with maximum 4 vertical levels
- **Deep sitemaps** - large websites (1,000+ pages) with 5 or more vertical levels

# Homepage layouts

![Homepage layouts](/images/homepage-layouts.png)

## Homepage layouts

Homepages serve as the entry point for websites. Good layout guides users and helps them find information quickly.

Always select the layout that best serves your users rather than following current trends. The UX design industry constantly evolves, and what's trending may not reflect best usability or accessibility.

## 1. Single-column

- **Structure** - one vertical column for content
- **Characteristics** - simplest layout option with logical top-to-bottom stacking (navigation → content → footer)
- **Best for** - mobile websites, reading-focused content, emphasizing one main element
- **Advantage** - easy scrolling and focus on text

## 2. Multicolumn

- **Structure** - two or more columns for content
- **Key element** - clear **focal point** (specific area capturing user attention)
- **Content distribution** - supporting content occupies 25-45% of page
- **Design principle** - uses visual weight and hierarchy
- **Common use** - desktop websites, above-the-fold content display
- **Pro tip** - one column often reserved for ad space

## 3. Box

- **Structure** - boxes/squares of varying sizes and proportions
- **Visual equality** - same-sized, evenly-spaced boxes = equal importance
- **Emphasis technique** - larger or separated boxes draw attention
- **Common applications** - e-commerce homepages (e.g., Amazon), UX portfolios, seasonal content rotation
- **Advantage** - easy content swapping

## 4. Featured image (Single image)

- **Structure** - single dominant image/video occupying entire page
- **Purpose** - create strong first impression and emotional connection
- **Requirements** - high-quality, message-relevant imagery
- **Navigation** - often includes sticky/fixed menu bar
- **Best for** - product pages, brand storytelling

## 5. Asymmetrical

Purposefully imbalanced designs emphasizing specific elements through natural eye-tracking patterns:

### **F-Shape Eye-Tracking Pattern**

- **User behavior** - browse content following F-shape
- **Best for** - text-heavy pages, search results
- **Design priority** - most important information at top
- **User tendency** - won't read to bottom

### **Z-Shape Eye-Tracking Pattern**

- **User behavior** - left to right → diagonal left → right again
- **Natural pattern** - mimics Western left-to-right, top-to-bottom reading
- **Best for** - sites with less content
- **Accessibility note** - users with visual impairments follow same patterns with assistive technology

## 6. Grid of Cards

- **Structure** - series of uniform-sized rectangular cards previewing content
- **Distinction from box layout** - cards are interrelated within same list (vs. independent boxes)
- **Technical features** - card/list view switching, lazy loading
- **Responsive design** - card size adapts to screen size
- **Common applications** - recipe blogs, streaming services (YouTube, Pinterest, TED)

## 7. Tiered Layer Cake

- **Structure** - stacked horizontal rows with varying column counts per layer
- **Flexibility** - inconsistent column numbers across layers
- **Responsive design advantage** - layers easily rearranged or swapped for different screen sizes
- **Distinction** - no all-encompassing container or long sidebars (unlike multicolumn)
- **Desktop to mobile** - multiple columns collapse to single column

## Takeways

1. **Simplicity vs. Complexity** - choose layout complexity based on content needs and screen size
2. **Responsive design** - different layouts may be appropriate for different device sizes (single-column for mobile, multicolumn for desktop)
3. **Visual hierarchy** - all layouts should consider hierarchy, color, and variety in element organization
4. **Focal points** - multicolumn and featured image layouts particularly benefit from clear focal points
5. **Purpose-driven design** - each layout serves specific purposes:
   - Single-column: reading and simplicity
   - Multicolumn: content variety and desktop optimization
   - Box: organization and categorization
   - Featured image: impact and emotion
6. **Quality matters** - especially for featured image layouts, high-quality visuals are essential
7. **Navigation consistency** - fixed/sticky navigation bars help maintain user orientation

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

## Above the fold

**Above the fold** is content on webpage that doesn't require scrolling to experience.

## Lorem Ipsum

**Lorem Ipsum** is placeholder text used in design to fill space where real content will eventually go. Lorem ipsum allows designers to visualize text-heavy areas without being distracted by actual content meaning.

## Icon placeholders

Icon placeholders are visual markers used in wireframes to indicate where icons will appear in the final design. They help designers plan layout and spacing for functional icons without committing to specific icon designs during the wireframing phase.

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
- **Space-saving elements** - hamburger menus, cards, carousels
- **Reduce clutter** - prioritize usability and accessibility

## Sketching paper wireframes

### Preparation

1. **List required information** - document all elements needed on page (navigation, images, text descriptions)
2. **Reference sitemap** - use sitemap to determine page structure and element prioritization
3. **Gather materials** - grid paper (or template), pen/pencil

### Drawing process

1. **Create multiple variations** - sketch 4-5 different layout versionss. Each version should have different design solutions.
2. **Consider all device types** - sketch wireframes for each device type and screen size.
3. **Top-to-bottom approach** - it is recommended to use *top-to-bottom* design approach. That is how users experience webpage.

### Review and refinement

1. **Identify best elements** - Mark favorite features from each wireframe
2. **Combine marked elements** - Create final wireframe integrating best components
3. **Repeat for all pages** - Apply same process to remaining website pages

### Documentation

1. **Note design decisions** - note reasoning behind breakpoint decisions, element positions on different devices
2. **Document wireframe progression for portfolio**
3. **Document takeaways** - write down what you have learned

## Best practices

1. **Focus on structure, not aesthetics** - detailed design comes later
2. **Iteration is essential** - designs evolve throughout the process
3. **Grid paper benefits** - enables consistent scaling and element proportion
4. **Industry standards** - facilitate team communication and understanding
5. **Progressive refinement** - paper sketches → digital wireframes
6. **Use standard visual conventions** - improves communication with team members
7. **Always reference sitemap** - ensures all required elements are included

## Transition to digital versions

After completing paper wireframes for all screen sizes, transition to digital wireframing tools to refine designs and prepare for prototyping. At this point placeholders should be filled with images or components.

### Applying layout grid in Figma

1. **Select Frame**
   - Click on frame where layout grid is needed
   - Ensure correct frame is active

2. **Access Layout Grid Section**
   - Right-hand sidebar
   - Find **Layout Grid** section
   - Click **"+" button** to create new grid

3. **Open Grid Panel**
   - Click **grid icon** to left of new grid
   - Opens detailed grid settings panel

4. **Change View to Columns**
   - Use drop-down menu
   - Change from **Grid** to **Columns**
   - This creates columnar structure

5. **Adjust Grid Properties**
   - Enter **count** of columns
   - Choose **color** for visibility
   - Adjust other properties:
     * Type
     * Width
     * Gutter size
   - Customize according to design requirements

6. **Finalize Settings**
   - Close panel when complete
   - Or click outside grid settings panel
   - Grid now active on frame

### Tips

- Upload paper wireframe photos to Figma for constant reference
- Set up grid system once, then duplicate frame for other pages
- Create reusable components for repeated elements (navigation, footer)
- Use keyboard shortcuts
- Use same placeholder conventions across all pages
- Keep visual hierarchy consistent
- Apply same fold principles to every page

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
9. **Wireframes are only blueprints** - They're meant to be rough, fast, and iterative. The goal is exploring ideas, not creating polished designs at this stage.

# Common components

![Common components](/images/common-website-components.png)

## Quick reference table

| Element | Description | Use Case |
|---------|-------------|----------|
| **Headings** | Titles or subtitles that organize content into clear sections using hierarchical levels (H1-H6). Larger and bolder than body text with increased spacing to establish visual hierarchy and content structure | Organizes content for visual scanning and enables screen reader navigation to specific sections |
| **Hamburger menus** | Collapsible navigation with three-line icon. Hide full navigation lists behind a clickable icon, revealing them only when needed (vs. showing all navigation links at once) | Condenses navigation lists for small screens |
| **Cards** | Surfaces containing content about a single subject. Fit related information into compact, stackable units that can be arranged efficiently in vertical columns on narrow screens | Organizes information in scannable, stackable units |
| **Carousels** | Scrollable feeds of images or cards. Allow multiple images/items to occupy the same horizontal space by letting users swipe through them sequentially (vs. displaying all items side-by-side) | Displays multiple items in limited horizontal space |
| **CTA buttons** | Call-to-action buttons that prompt users to take specific actions. Feature prominent styling with action-oriented text (e.g., "Get Started", "Buy Now", "Sign Up") to drive conversions and guide users toward desired outcomes | Drives user actions and conversions with clear, visible prompts |
| **Icons** | Simple visual symbols replacing text labels in mobile interfaces. Provide compact shortcuts for common actions (search, cart, account, menu) using universally recognized imagery instead of words | Maximizes limited screen space while maintaining functionality |

## Headings

### Purpose

Headings are titles or subtitles that organize website content into clear sections and establish visual hierarchy. They help all users navigate and scan content efficiently while enabling screen reader users to jump directly to specific sections without experiencing the entire page sequentially.

### Visual characteristics

- Larger font size than body text (H1: 32-48px, H2: 24-32px, H3: 20-24px)
- Bolder weight than surrounding text (600-700)
- Increased spacing above and below (16-32px margins)
- Clear visual hierarchy showing importance levels

### Functionality

**Visual hierarchy support:**
- Creates clear organizational structure for sighted users
- Guides eye movement through page content
- Enables quick content scanning and comprehension

**Screen reader navigation:**
- Screen readers navigate via headings menu
- Users listen to list of all headings at once
- Users jump directly to desired heading
- Dramatically faster than listening to entire page

### Placement and usage

**Heading hierarchy:**
- **H1** - main page title (one per page)
- **H2** - major section headings
- **H3** - subsections within H2 sections
- **H4-H6** - further nested subsections as needed

**Best practices:**
- Never skip heading levels (H1 → H2 → H3, not H1 → H3)
- Don't use headings for styling only
- Maintain logical document outline
- Keep heading text concise (5-10 words maximum)
- Annotate heading levels in wireframes for developer handoff
- Test with screen readers to verify navigation flow

## Hamburger menu icon

### Purpose

The hamburger menu icon toggles hidden navigation menus, primarily for responsive web design. It saves screen space, maintains clean interfaces, and provides a universally recognized symbol for collapsed navigation on mobile and small screens.

### Visual characteristics

- Three horizontal lines stacked vertically with equal spacing
- Uniform line thickness and equal length
- Minimal, unambiguous design
- Monochromatic, matching site color scheme
- Square aspect ratio (approximately 1:1)
- Typical size: 24x24px to 48x48px

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
- **Mobile** - top-left corner (most common) or top-right corner (RTL interfaces)
- **Desktop/Tablet** - less common; used in header when full navigation doesn't fit
- **Fixed position** - often remains visible while scrolling

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
- **Clickable** - entire card navigates to detail page
- **Action-based** - multiple buttons for specific actions
- **Informational** - display-only with possible interactive elements
- **Expandable** - reveals additional content on interaction
- **Selectable** - multi-select with checkboxes

**Features:** Dynamic updates, lazy loading, filtering/sorting, keyboard navigation, screen reader support, semantic HTML with ARIA labels, minimum touch targets (44x44px)

### Placement and usage

**Layout patterns:**
- **Grid** - responsive columns (1 mobile, 2-3 tablet, 3-4 desktop) with 16-32px gaps
- **List/Feed** - single column, full-width stacked vertically
- **Masonry** - variable heights for dynamic layouts
- **Dashboard** - mixed sizes (1x1, 2x1, 2x2) for metrics

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
- **Arrow buttons** - previous/next controls on left/right edges
- **Indicator dots** - clickable position markers below carousel
- **Touch gestures** - swipe left/right on mobile devices
- **Keyboard** - arrow keys for navigation, Tab for focus
- **Auto-play** - automatic rotation with configurable interval (3-5 seconds typical)

**Features:** Infinite loop (cycles back to start), pause on hover/interaction, lazy loading for performance, responsive resizing, optional thumbnails preview

**Accessibility:** ARIA roles (`role="region"`, `aria-roledescription="carousel"`), keyboard navigation, pause controls, screen reader announcements for slide changes

### Placement and usage

**Layout patterns:**
- **Hero section** - full-width at top of page for featured content
- **Product gallery** - product detail pages with image carousel
- **Content showcase** - homepage sections highlighting features or offerings
- **Testimonials** - customer reviews or quotes rotation

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
- **Submit forms** - complete purchases, registrations, or data submissions
- **Navigate** - direct users to landing pages, product details, or key sections
- **Download** - trigger file downloads or app installations
- **Share/Save** - enable social sharing or content bookmarking
- **Contact** - open contact forms, chat, or email clients

**Interaction behavior:** Single click/tap triggers action, provides immediate feedback (loading states, confirmation messages), prevents double-submission, accessible via keyboard (Enter/Space)

**Features:** Clear action text (2-5 words), sense of urgency when appropriate ("Get Started Now", "Limited Offer"), tooltip on hover for additional context, icon support for visual reinforcement

### Placement and usage

**Strategic placement:**
- **Hero section** - primary CTA above the fold for maximum visibility
- **End of content** - after value proposition or product description
- **Navigation bar** - top-right corner for persistent access
- **Modals/Forms** - bottom-right or centered for form submission
- **Cards** - bottom or top-right within card boundaries

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

## Icons

### Purpose

Icons replace text labels in mobile interfaces to maximize limited screen space while maintaining functionality. They serve as compact visual shortcuts for quick recognition and interaction, reducing clutter and improving navigation efficiency on small screens.

### Visual characteristics

**Structure:**
- Simple, recognizable symbols representing actions or concepts
- Minimal visual complexity for quick comprehension
- Consistent visual style across entire interface
- Monochromatic or limited color palette
- Typical size: 24x24px to 48x48px

**Variations:** Filled vs. outlined styles, active vs. inactive states, labeled icons (icon + minimal text), icon badges (notification counters)

### Functionality

**Space efficiency:**
- Reduces horizontal space by 60-80% compared to text labels
- Allows more navigation options in limited screen width
- Frees vertical space for primary content

**User benefits:**
- Faster visual scanning than reading text
- Language-independent communication
- Instant recognition for common actions
- Reduced cognitive load through familiar symbols

**Common icon replacements:**
Search → magnifying glass, Shopping Cart → cart, User Account → person/avatar, Menu → hamburger, Share → share arrow, Favorites → heart, Settings → gear, Home → house

### Placement and usage

**Optimal placement:**
- **Top navigation** - primary actions (search, cart, account) right-aligned
- **Bottom navigation** - 3-5 main sections as icon-only tabs
- **Floating action buttons** - primary action icon prominently displayed

**When to use icons:** Screen width under 768px, universally recognized actions, repeated actions across screens, status indicators requiring minimal space

**When to keep text:** Primary CTAs (conversions matter), unfamiliar actions, complex concepts, first-time experiences, accessibility-critical actions

**Best practices:**
- Use standard, widely-recognized icons
- Maintain minimum 44x44px touch targets
- Provide aria-label for screen readers
- Test icon recognition with users
- Ensure 3:1 minimum color contrast

**Responsive strategy:**
Desktop (text + icons), Tablet (selective mix), Mobile (icon-only for secondary actions, labeled for primary CTAs)

## Choosing components for your project

1. **Navigation needs**
   - How many navigation items?
   - Will they fit horizontally on mobile?
   - Consider: Hamburger menu

2. **Content volume**
   - Lots of similar items to display?
   - Need scannable organization?
   - Consider: Cards

3. **Visual content**
   - Multiple images to showcase?
   - Limited screen space?
   - Consider: Carousel

4. **User actions**
   - Key actions users should take?
   - Need to drive conversions?
   - Consider: CTA buttons

# Gestalt principles

![Gestalt principles](/images/gestalt-principles.png)

## What are Gestalt principles?

Originating from Gestalt psychology in the 1920s, these principles explain how people naturally group visual elements, recognize patterns, and simplify complex images into organized, meaningful wholes.

Gestalt principles guide how UX designers organize interface elements to create intuitive, visually coherent experiences that align with natural human perception patterns.

## Why they matter?

- **Reduces cognitive load** - helps users process information faster by leveraging natural perception patterns
- **Improves usability** - creates intuitive interfaces that feel natural to navigate
- **Enhances visual hierarchy** - guides user attention to important elements
- **Increases comprehension** - makes complex information easier to understand
- **Strengthens communication** - ensures design intent matches user perception
- **Creates visual harmony** - produces aesthetically pleasing, organized layouts

## 1. Proximity

***Elements close to each other are perceived as related or belonging to the same group.***

**How it works:**
- Spatial distance indicates relationships between elements
- Closer elements = stronger perceived connection
- White space separates unrelated groups

**UX applications:**
- Group form labels with their input fields
- Cluster navigation items into logical sections
- Separate content blocks with white space
- Position related buttons together (e.g., "Save" and "Cancel")

**Example:**

Navigation menus group related links together with spacing between different categories.

**Best practices:**
- Use consistent spacing within groups
- Increase spacing between unrelated elements (at least 1.5x internal spacing)
- Don't rely on proximity alone for critical relationships

## 2. Similarity

***Elements sharing visual characteristics (color, shape, size, orientation) are perceived as related or part of the same group.***

**How it works:**
- Similar visual appearance suggests similar function or category
- Works across multiple attributes: color, shape, size, texture, typography
- Overrides proximity when strong enough

**UX applications:**
- Use consistent button styles for similar actions
- Apply same color to all clickable links
- Match card designs for similar content types
- Unify icon styles throughout interface

**Example:**

All primary CTA buttons share the same color and style, making them instantly recognizable.

**Best practices:**
- Maintain consistent styling for same element types
- Use visual differences to indicate different functions
- Don't make unrelated elements look similar

## 3. Closure

***People mentally complete incomplete shapes or patterns, filling in missing information to perceive whole objects.***

**How it works:**
- Brain fills gaps to see complete forms
- Works with interrupted lines, partial shapes, negative space
- Allows simplified, minimal designs

**UX applications:**
- Use incomplete circles for loading indicators
- Create icons with minimal lines that suggest full shapes
- Design logos with negative space
- Employ progress indicators with partial fills

**Example:**

Hamburger menu icon (three lines) suggests a complete menu without showing all elements.

**Best practices:**
- Ensure missing parts are predictable
- Don't make users work too hard to complete the image
- Test with users to verify recognizability

## 4. Continuity (Continuation)

***Elements arranged on a line or curve are perceived as related and following a path, and the eye naturally follows continuous lines.***

**How it works:**
- Eyes follow smooth paths rather than jumping between disconnected elements
- Prefers continuous, flowing arrangements
- Creates visual flow and direction

**UX applications:**
- Design navigation bars with linear arrangement
- Create visual flow through page layouts (F-pattern, Z-pattern)
- Connect related elements with lines or arrows
- Design step indicators showing sequential progress

**Example:**

Breadcrumb navigation creates continuous path showing user location.

**Best practices:**
- Align elements along clear paths (horizontal, vertical, curved)
- Use continuation to guide eye movement toward important content
- Avoid disrupting natural flow with misaligned elements

## 5. Figure/Ground (Figure-Ground)

***People instinctively separate visual elements into foreground (figure) and background (ground), distinguishing objects from their surroundings.***

**How it works:**
- Creates depth and focal hierarchy
- Contrast helps define figure vs. ground
- Can be ambiguous or clearly defined

**UX applications:**
- Use modal overlays with darkened backgrounds
- Create cards with shadows to lift content from background
- Design hero sections with contrasting foreground text
- Employ color contrast to highlight interactive elements

**Example:**

Modal dialogs appear as figures over dimmed background, focusing user attention.

**Best practices:**
- Ensure sufficient contrast between figure and ground (4.5:1 for text)
- Use shadows, borders, or color to define separation
- Make important elements clearly distinguishable from background

## 6. Common fate

***Elements moving in the same direction, at the same speed, or changing together are perceived as a unified group.***

**How it works:**
- Synchronized movement creates perceived relationship
- Applies to animation, scrolling, transitions
- Overrides static grouping principles when active

**UX applications:**
- Animate related elements together (e.g., menu items sliding in)
- Scroll related content in sync (parallax effects)
- Show grouped items responding to same interaction
- Transition card sets simultaneously

**Example:**

Notification cards dismissing together when "Clear All" is clicked.

**Best practices:**
- Use consistent animation timing for related elements
- Keep animations smooth and synchronized
- Don't overuse—can become distracting

## 7. Symmetry

***Symmetrical elements are perceived as belonging together and forming coherent, stable shapes, even when separated by distance.***

**How it works:**
- Creates sense of balance and order
- Brain naturally seeks symmetrical patterns
- Can be vertical, horizontal, or radial symmetry

**UX applications:**
- Center-align logos and headlines for balance
- Create symmetrical button layouts (e.g., "Cancel" and "Confirm")
- Design balanced grid layouts
- Use symmetrical icon designs

**Example:**

Login forms with vertically symmetrical input fields create organized, balanced appearance.

**Best practices:**
- Use symmetry for formal, professional designs
- Break symmetry intentionally to draw attention
- Balance symmetry with visual interest

## 8. Common region

***Elements enclosed within the same boundary (border, background color, container) are perceived as grouped together.***

**How it works:**
- Visible boundaries create strong grouping
- Works with boxes, borders, background colors, containers
- One of the strongest grouping principles

**UX applications:**
- Use cards to contain related information
- Create bordered sections for form groups
- Apply background colors to distinguish content areas
- Design panels or containers for widgets

**Example:**

Dashboard widgets enclosed in bordered cards clearly separate different data sets.

**Best practices:**
- Use subtle borders or backgrounds (avoid heavy visual weight)
- Ensure clear visual separation between regions
- Don't over-containerize—can create cluttered appearance

## Applying Gestalt principles in practice

1. **Audit existing designs** - identify which principles are (or aren't) being applied
2. **Plan visual groupings** - decide which elements should be perceived together
3. **Use consistent patterns** - apply principles consistently across entire interface
4. **Test with users** - verify that perceived groupings match intended organization
5. **Iterate based on feedback** - adjust spacing, styling, and organization as needed

## Using Gestalt principles in common components

- **Navigation menus** - Proximity (grouped items) + Similarity (consistent styling) + Common Region (bordered containers)
- **Form design** - Proximity (labels near inputs) + Common Region (fieldsets) + Continuity (vertical flow)
- **Card layouts** - Common Region (borders) + Similarity (uniform cards) + Proximity (grouped within sections)

## Common mistakes to avoid

- **Inconsistent spacing** - undermines proximity principle
- **Too many visual styles** - confuses similarity-based groupings
- **Overcrowding** - prevents clear figure/ground separation
- **Breaking expected patterns** - disrupts continuity and flow
- **Over-reliance on single principle** - combine multiple principles for clarity

# Low-fidelity prototypes

![Low-fidelity prototypes](/images/low-fidelity-prototypes.png)

## What are prototypes?

UX prototypes are interactive models of a product used to test ideas before building the final version. Prototypes help designers gather user feedback and identify problems early in the design process.

## Low-fidelity vs. High-fidelity prototypes

Low-fidelity prototypes (lo-fi prototypes) are simple, basic structures that communicate big-picture design concepts and test navigation flow, while high-fidelity prototypes (hi-fi prototypes) are polished designs with full functionality that closely match the final product.

## Low-fidelity prototypes vs. wireframes

While both are simple versions with minimal content, they serve different purposes:

- **Wireframes** - blueprints of product structure only
- **Lo-fi prototypes** - connect wireframes together with functionality and navigation

## When to build low-fidelity prototypes

Build them after you've designed wireframes and you want to test if users can successfully navigate the designs to complete tasks.

## Purpose of testing

Testing prototypes helps:
- Identify and solve problems related to website function
- Test how the website works with real people
- Gather user feedback before investing in high-fidelity designs

## Workflow

Wireframes → Low-fi prototypes → Testing → High-fi prototypes → Testing → Final Product

## User flows

User flows are the paths users take through a product to complete specific tasks. User flows help designers plan navigation and ensure users can successfully accomplish their goals.

A prototype is always built around testing the user flow that solves the user problem.

Before building, ask yourself:
1. How will users navigate through the necessary pages?
2. How will users go from one page to the next?

A good user flow should allow users to:
- **Move forwards and backwards** through the prototype
- **Enter from different starting points**
- **Clearly understand** when the flow has ended
- **Return to the entry point** after completing the interaction

## Example: checkout flow for buying t-shirts

1. Navigate to the women's section
2. Choose a t-shirt
3. Select the color and size
4. Add it to the cart
5. Continue to checkout
6. Fill in e-mail address
7. Choose a shipping option
8. Enter payment and billing information
9. Click "Place order"

## Entry points

Entry points are starting locations where users begin their interaction with the website.

Key questions to consider when defining entry points:
- What do I want my user to be able to do?
- How will my users navigate through the website structure?
- Where do I want them to start their journey?

## Prototyping in Figma

Prototype mode:
1. Open your digital wireframe project
2. Go to the right sidebar
3. Click the **Prototype** tab to create user interaction flows between pages

Connecting frames:
1. Click the first item in the user flow
2. A blue circular node appears on the right side
3. Click and drag the blue arrow to the destination item on another frame
4. Release the mouse to complete the connection

Creating user flow:
- Work carefully following your intended user flow as a guide
- Create all necessary interactions using the same connection process
- **Preview your work**: Click the **Play** icon to test
- Test all buttons and connections to ensure they work correctly
- Connect all wireframes necessary for the main user flow

## Quality checklist

When evaluating your own low-fidelity prototype, ask yourself:
1. **Structure & flow** - does it connect **at least four distinct wireframes**? Does it allow completion of a **main user flow**?
2. **Navigation** - can users move **forward and backward**? Are there **clear navigation cues**? Are there **multiple entry points**?
3. ** Completion & feedback** - are there **messaging or navigational cues** that indicate successful completion? Can users **return to the starting point** after completing the flow sequence?

# Mockups

## Mockups vs wireframes

Wireframes are simple sketches or outlines that show the basic structure and layout of a screen or product. You can draw them on paper or create them digitally, but they don't include colors or detailed design elements.

Mockups are more polished versions that look closer to the final product. They include colors, fonts, and icons to show what the design will actually look like, but you can't click or interact with them yet.

| Wireframes | Mockups |
|------------|---------|
| Static images | Static high-fidelity designs |
| Show page layout & hierarchy | Show visual details & UI elements |
| No color or detail | Include color, typography, iconography |
| Outline content structure | Represent near-final appearance |
| Blueprint phase | Visual refinement phase |

## Transition to mockups

Creating mockups from wireframes isn't just about copying what you already have. You should make improvements and changes to ensure the design looks good, works well for users, and is accessible to everyone. Like wireframes, you'll create multiple versions of your mockups, getting feedback each time and continuously improving them until they're ready.

# Visual design

## What is visual design?

**Visual design** refers to how a product or technology appears to the user.

The three main elements of visual design are typography (text and fonts), color, and iconography (icons and symbols). These elements work together to make designs look good, help users navigate easily, communicate information clearly, and keep the brand looking consistent.

## Typography

**Typography** is the practice of arranging text and typefaces (fonts) to make language legible, readable, and visually appealing.

- Adds hierarchy to designs
- Makes text easy to read
- Adds visual style

## Color

**Color** is one of the most impactful visual design elements.

- How color communicates messages and emotions?
- How people understand color?
- How colors mix, match, or contrast?

- **Red:** Attracts attention
- **Blue:** Communicates serenity, calmness, and peace

## Iconography

**Iconography** are images or symbols associated with a subject or idea. For example Power icon = circle with a line (⏻)

- Icons limits used text space
- Icons and symbols catch the user's attention
- They provide easy transitions to other pages or locations

## Layouts

Beyond typography, color, and iconography, successful designs require careful consideration of **layouts** and how elements are arranged on a page. Great layouts present information in a logical way, making important elements standout.

There are three key tools for effective layouts:
- Grids
- Containment
- Negative space

## Grids

Lines that are evenly spaced to help you design consistently and manage the spacing of elements.

**Layout grid:**
- Vertical columns with spaces (alleys) between them
- Common for responsive web design
- Helps align elements consistently

**Uniform Grid:**
- Intersecting vertical and horizontal lines
- Creates a matrix of evenly spaced guidelines
- Called "Uniform Grids" in Figma

## Containment

Visual barriers that keep designs neat and organized.

There are four methods for containment: dividers, borders, fill, shadows.

### Method 1: Dividers

**Dividers** are single lines to separate sections of a page.

- Separating list items
- Dividing content sections
- Creating visual breaks between information

**Example:**
Horizontal lines separating messages in an inbox.

### Method 2: Borders

**Borders** are continuous lines forming shapes (squares, rectangles) to break up sections.

- Highlighting selections
- Grouping related content
- Creating distinct content areas
- Showing interactive states

**Example:**
Borders around size options (pink borders for unselected, black for selected).

### Method 3: Fill

Shapes should have colors inside.

- Creating prominent call-to-action buttons
- Distinguishing different element states
- Adding visual emphasis
- Creating depth and hierarchy

#### Method 4: Shadows

**Shadows** are creating dimension in combination with borders or fill.

**Key characteristics:**
- Add depth to designs
- Signal interactivity (e.g., selected items)
- Shadow depth can change element perspective
- Vary from subtle (2px) to dramatic (24px)

**Use Case:**
- Indicating selected items
- Creating card-style layouts
- Showing elevated elements
- Adding realistic depth

## Negative space

**Negative space** is the area that surrounds an object within an image; the gaps between elements or space not being used.

**Improves readability:**
- Helps users read content more easily
- Reduces visual clutter
- Prevents information overload

**Enhances identification:**
- Makes important information stand out
- Guides user attention
- Creates visual hierarchy

**Visual appeal:**
- Makes content easier to engage with
- Creates a cleaner, more professional look
- Provides visual rest areas

| Less negative space | More negative space |
|---------------------|---------------------|
| Crowded elements | Spacious layout |
| Harder to read | Easier to read |
| Overwhelming | Calm and organized |
| Less engaging | More visually appealing |

## Emphasis

**Emphasis** is about making **the most important parts of your design stand out** so users notice them first. You can do this by making key elements larger, brighter, or more prominent than other elements. This helps guide users to the most important content or actions they need to take.

## Hierarchy

Hierarchy is about **organizing your design so users can easily see what's most important**. You do this by making important elements bigger and brighter, while less important elements are smaller and less noticeable. This creates a clear order that helps users understand what to look at first and guides them through the content naturally.

## Scale

Scale is about **changing the size of elements to show how important they are** and create visual contrast. By making some elements bigger and others smaller, you can draw attention to specific parts of your design. Even when you change the size, the elements should still be easy to recognize.

## Proportion

Proportion is about **keeping consistent size relationships between elements** in your design. When you change the size of elements, they should maintain the same ratio to each other, which creates a balanced and harmonious look. This ensures that all parts of your design feel like they belong together and look visually pleasing.

## Unity

Unity is about **making all parts of your design feel connected and like they belong together**. You achieve this by grouping related elements together and using consistent colors, styles, and patterns throughout your design. This creates a cohesive look that feels like one complete design rather than separate pieces, and helps strengthen the brand's identity.

## Variety

The variety principle involves **introducing different shapes or patterns with the same size and color to make designs more interesting**. It helps stop designs from looking boring and keeps users interested. The trick is to add enough variety to be interesting, but not so much that the design looks chaotic or confusing.

# Design systems

## What is a design system?

Design system is a series of reusable elements and guidelines that allow teams to design and develop a product following predetermined standards. Think of it as a comprehensive toolkit and rulebook for creating consistent designs across all products and platforms.

## Benefits of using design system

- **Consistency** ensures designers work in a standardized way while users get familiar, predictable experiences that reinforce brand identity.
- **Scalability** makes it easy to expand designs to new products and platforms while maintaining consistency.
- **Efficiency** saves time and money by eliminating the need to redesign common elements and enabling faster prototyping.
- **Collaboration** improves by creating a common language between designers and developers, making it easier to onboard new team members and communicate design decisions clearly.

## Components of a design system

Design systems have four main components that work together to create consistent products.

1. **Visual styles** - include typography, color palettes with HEX codes, and iconography to express the brand consistently across all touchpoints. 
2. **Guidelines** - provide design principles and rules that help designers make consistent decisions about when and how to use components.
3. **UI components** - are ready-to-use interface elements like buttons, cards, and forms that maintain consistency and speed up the design process.
4. **Supporting code for developers** - gives developers the technical specifications and code snippets they need to build the designs correctly and bridge the gap between design and development.

## Sticker sheets

Sticker sheet is a frame within Figma where you **save colors and components that you can copy-and-paste into designs**. Sticker sheet is your design toolkit - a centralized collection of all reusable design elements that ensures consistency, saves time, and facilitates collaboration. 

What to include in a sticket sheet?
- Components
- Typography
- Color
- Iconography

- Sticker sheets are **essential** for maintaining consistency
- Larger companies have **comprehensive design systems** built on this concept
- **Time saved** using sticker sheets = more time for creative problem-solving
- Sticker sheets are often **shared across teams** for collaboration
- They serve as **living documentation** of design decisions

## Popular big company design systems

- Google Material Design
- Apple Human Interface Guidelines
- Microsoft Fluent Design System

## UI kits

UI kit is a **collection of elements, components, and files** that help UX designers create apps and websites.

Figma Community has numerous UI kits available for download.

What's included
- Pre-designed components (buttons, cards, forms)
- Typography sets
- Icon libraries
- Color palettes
- Layout templates

**Key difference:** UI kits are like simplified design systems - they include design components you don't need to create yourself.

## Applying for your project

Step 1: Apply visual design principles to your mockups
- Review each principle
- Identify where to apply them
- Iterate based on principles

Step 2: Create a simple sticker sheet
- Collect your most-used components
- Organize by category
- Label everything clearly
- Use consistent spacing

Step 3: Explore existing design systems
- Study major company systems
- Download and experiment with UI kits
- Understand why certain decisions were made
- Apply learnings to your own work

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
- Common components
  - https://www.pexels.com/pl-pl/zdjecie/burger-z-plasterkami-warzyw-z-bliska-fotografia-2702674/
- Gestalt principles
  - https://unsplash.com/photos/N7G5xtR28fo
- Low-fidelity prototypes
  - https://www.pexels.com/pl-pl/zdjecie/selektywna-ostrosc-fotografii-zoltego-samochodu-zabawkowego-243206/