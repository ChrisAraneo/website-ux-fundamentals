# GitHub Copilot Custom Instructions - UX Design Fundamentals

## Project Context
This project contains summaries of educational materials found online on User Experience. The educational summaries are generated based on content provided by the user in prompts.

## Primary Use Case
When working with content in this repository, assist with creating summaries that will be the best study materials. When given prompts, generate detailed summaries that capture the key concepts and information. Use your own knowledge to enhance the summaries where appropriate. You should create summaries of the educational materials provided in the repository files. Use your own knowledge to extend and enhance the learning materials where appropriate.

## Style Guidelines

### Clear and Concise Language
Use clear and concise language suitable for educational content.

### Avoid Simple Lists
Where possible, avoid lists with short list items (less than one sentence) and bullet points. Instead, use full sentences and paragraphs to explain concepts in detail. Make key phrases bold to highlight important information.



**Example**: Instead of writing:
```
Finalize all visual elements within the prototype, including:
- Color
- Images
- Icons
- Typography
- Written content
- Illustrations
- Graphics
- External links
```
Write:
```
**Finalize all visual elements** within the prototype, including color, images, icons, typography, written content, illustrations, graphics, and external links.
```

### Use Numbered Lists With Complex Concepts Or Steps
When dealing with similar complex concepts, that cannot be easily explained in a sentence or two, use lists to break down the information.

Use numbered lists when listing multiple complex concepts that require one or two sentences description for better understanding. Also use numbered lists for step-by-step instructions.

**Example**:
```
### Creating connections in Figma
1. **Select the hotspot** - the item where the user's interaction will take place (button, icon, heading, etc.)
2. **Make the connection** - the arrow (also called "noodle") that connects the hotspot to the destination
3. **Indicate the destination** - where the connection ends (must be a frame or screen, not an item within a frame)
```

### Avoid Using Checkboxes
Avoid using checkboxes in lists. Instead, use descriptive sentences to convey the same information.

**Example**: AVOID writing:
```
- [ ] All interactive elements connected
- [ ] Hotspots properly defined
- [ ] Connections lead to correct destinations
- [ ] Starting frame is the first user action
```
INSTEAD, write:
```
Ensure that all interactive elements are connected, hotspots are properly defined, connections lead to correct destinations, and the starting frame is the first user action.
```

### Avoid Using Bold Headings
Avoid using bold text and immediately following it by lists.

**Example**: AVOID writing:
```
**How to use**:
- Use numbers in circles to indicate navigation order
- Show the number of key presses or tabs from one item to the next
- Standard navigation order: upper-left to lower-right
- Annotate any elements that fall outside standard order
```

INSTEAD, write:
```
### How to use annotations?
To use annotations effectively:
- **Numbers in circles** - use numbers in circles to indicate navigation order.
- **Number of key presses** - show the number of key presses or tabs from one item to the next.
- **Standard navigation order** - follow the standard navigation order from upper-left to lower-right, and annotate any elements that fall outside this standard order.
```
