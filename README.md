# Bike-Color
https://karaki326.github.io/Bike-Color/
This HTML project represents a simple, interactive webpage for the Honda CB300R motorcycle. The page combines an attractive design and functional JavaScript to create a dynamic color-selection experience for users.
This HTML project represents a simple, interactive webpage for the Honda CB300R motorcycle. The page combines an attractive design and functional JavaScript to create a dynamic color-selection experience for users.

### Project Overview:

- **Purpose**: Showcases the Honda CB300R motorcycle and allows users to select different color options for the bike's display background.
- **Layout and Styling**:
  - The webpage is structured with a navigation bar and a main content area within a centered container.
  - The **navigation bar** includes a logo and a “Test Drive” link.
  - The **content area** displays information about the Honda CB300R, with a heading and description.
  - Styling is applied using an external CSS file, `style.css`, which defines layout, font, colors, and other visual elements.

### Features:

1. **Color Selection**: 
   - Below the description, users see three color circles (yellow, red, black) representing bike colors.
   - Each color circle is clickable, allowing users to change the background image of the container to reflect the chosen color.

2. **JavaScript Interactivity**:
   - JavaScript is used to add event listeners to each color circle.
   - When clicked, each color circle changes the `backgroundImage` property of the container, switching to a specific image file associated with that color.

### Key Components in Code:

- **HTML Structure**:
  - The content is wrapped in a `div` with the class `container`, which serves as the main visual area.
  - Within this `container`, there’s a `nav` section and a `div` for the bike’s content (headings, description, and color selection).
  
- **CSS Styling** (`style.css`):
  - The container occupies 80% of the viewport width and sets a default background image.
  - Flexbox is used for layout alignment within the navigation and color selector, giving a clean, centered look.
  - Specific colors and styles are set for headings, text, and background images.

- **JavaScript**:
  - JavaScript handles the color selection functionality by changing the background image of the container based on user interaction.

This simple yet engaging project provides users with an interactive experience while exploring different color options of the Honda CB300R motorcycle.
