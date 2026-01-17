# High-fidelity Prototypes

## High-fidelity prototypes

Prototype is an early model of a product that demonstrates functionality. **High-fidelity prototypes** are detailed, interactive versions of designs that closely match the look and feel of the final product.

## Interactive mockups

High-fidelity prototypes take the design work already done in mockups and make it interactive.

## Focus on functionality

Remember that mockups focus on visual design, while prototypes focus on functionality.

## Three core pieces of high-fidelity prototypes

### 1. Visual elements
Finalize all visual elements within the prototype, including:
- Color
- Images
- Icons
- Typography
- Written content
- Illustrations
- Graphics
- External links

**Goal**: Use realistic content instead of placeholders to simulate the real app experience.

**Example difference**:
- Lo-fi prototype: Uses lines or placeholder text like "First name, Last name" or "Dog Walker A"
- Hi-fi prototype: Includes actual names, descriptions, and profile photos

### 2. Navigation
Finalize the navigation for the user flow you want to test. Navigation helps users explore and enjoy your product.

**Critical user journey**: The main user flow that should already be established in your low-fidelity prototypes.

**Why it matters**: Without good navigation, users will struggle or stop using your product.

**Navigation checklist**:
- How does a user get from one screen to the next?
- How easy is it to locate navigation-related icons (back arrows, X buttons)?
- At what point does the user journey end?
- Do you have the right buttons or icons on each screen?

### 3. Interactivity
Add interaction between each screen to make the prototype function. Interactivity includes gestures and motion.

**Creating connections in Figma**:
1. **Select the hotspot** - the item where the user's interaction will take place (button, icon, heading, etc.)
2. **Make the connection** - the arrow (also called "noodle") that connects the hotspot to the destination
3. **Indicate the destination** - where the connection ends (must be a frame or screen, not an item within a frame)

## Six-step process to create high-fidelity prototypes in Figma

### Step 1: Lay out the mockups
- Copy and paste mockups into the hi-fi prototype page
- Order screens based on the user flow
- Arrange in the sequence users would move through the app

**Pro tip**: Create your hi-fi prototype inside the same file as existing designs (wireframes and mockups) by creating a new page.

### Step 2: Connect the screens
1. Switch to **Prototype mode** in the right side panel
2. Select the item to be the hotspot
3. Click the **prototype node** (blue circle with plus sign)
4. Drag the arrow to the destination frame

**Important**: The first connection you make will be the starting frame for your prototype. Make sure the first connection is the first action you want a user to take.

### Step 3: Add interaction details
Add specific interactions and behaviors to connections (covered in advanced topics).

### Step 4: Adjust the animation
Fine-tune motion and transitions between screens.

### Step 5: Complete for all screens
Continue making connections throughout all screens in the user flow.

### Step 6: Share your work
Export or share the prototype for testing and feedback.

## Web accessibility for high-fidelity prototypes

### Web Content Accessibility Guidelines (WCAG)
WCAG documents explain how to make web content more accessible to people with disabilities. Most standards focus on incorporating text, sounds, and images in ways that support more users.

## Three ways to make web designs accessible

### 1. Annotations
**Annotations** are markers placed next to interactive UI elements (like call-to-action buttons) that demonstrate navigation flow.

**Purpose**:
- Indicate the **linear focus order** or **traversal order** for assistive technology like screen readers
- Set the order in which a user would tab through items using a keyboard instead of touchscreen or mouse

**How to use**:
- Use numbers in circles to indicate navigation order
- Show the number of key presses or tabs from one item to the next
- Standard navigation order: upper-left to lower-right
- Annotate any elements that fall outside standard order

**Who uses them**: Engineers use annotations to implement proper navigation order in development.

### 2. Hierarchical headings
**Hierarchy** is a visual design principle that orders elements on a page by importance.

**Headings** are named sections using different font sizes (larger than body text) that show hierarchy and help users navigate.

**Heading tags in HTML**:
- **H1** - Most important heading (often used for titles)
- **H2** - Subtitles or callout boxes
- **H3, H4, etc.** - Further hierarchy levels

**Why they matter**: Specific heading tags allow screen readers to understand page hierarchy and help users navigate from the screen reader menu options more easily.

### 3. Accessibility labels
**Labels** (also called screen reader verbalizations) add descriptive language to interactive UI elements on the webpage.

**What labels should indicate**:
- The purpose of the control
- The type or role of the control

**Example**: A floating action button in Gmail is labeled "compose" and the type is "button."

**Grouping similar controls**:
- Group related controls (like checkboxes) so assistive technology users understand relationships
- Helps users navigate to and from grouped elements quickly

**Who uses them**: Engineers use labels to determine the best implementation for the intended user experience.

## Additional accessibility considerations

### Accessible color and contrast
**Luminosity contrast ratio**: A measurement of contrast between background and text color.

**Best practices**:
- Light background with dark text, OR
- Dark background with light text

**Color combinations to avoid**:
- Red-green (problematic for colorblind users)
- Similar colors like light gray and white (low contrast sensitivity issues)

### Responsive accessibility
When designing responsive websites:
- Ensure all screen sizes are accessible
- Pages should automatically resize and rearrange when users zoom in or increase font size
- Avoid overlapping elements when sections are enlarged
- Create multiple mockup versions: default display and enlarged/zoomed display

**Why it matters**: Communicate different responsive interactions to engineers so magnification and accessibility requirements are built in before full development.

## Resources and standards

- **WCAG** - Web Content Accessibility Guidelines
- **ARIA** - Accessible Rich Internet Applications
- **HTML** - HyperText Markup Language (used for heading tags and structure)
- **Material Design** - Google's accessibility design guidelines
- **The A11Y Project** - Community resources for digital accessibility
- **WebAIM** - Contrast and color requirement guidelines

## Quality checklist

Before finalizing your high-fidelity prototype, verify:

**Visual elements**:
- [ ] All placeholder content replaced with realistic content
- [ ] Images, icons, and graphics finalized
- [ ] Typography consistent throughout
- [ ] External links functional

**Navigation**:
- [ ] User can move from screen to screen
- [ ] Navigation icons clearly visible
- [ ] User journey has clear beginning and end
- [ ] Back arrows and exit buttons present

**Interactivity**:
- [ ] All buttons and interactive elements connected
- [ ] Hotspots properly defined
- [ ] Connections lead to correct destinations
- [ ] Starting frame is the first user action

**Accessibility**:
- [ ] Navigation order annotated
- [ ] Hierarchical headings (H1, H2, H3) marked
- [ ] Interactive elements have labels
- [ ] Color contrast meets WCAG standards
- [ ] Responsive behavior documented
