# Info-6150-assignment-6
# Responsive Website with CSS Grid, Flexbox, and SASS/SCSS

This project demonstrates the use of modern CSS layout techniques like **CSS Grid**, **Flexbox**, and **SASS/SCSS** features to build a responsive website. The goal is to optimize CSS through modular design and ensure the layout adapts smoothly across different screen sizes.

## Table of Contents
- [Features Implemented](#features-implemented)
  - [CSS Grid Layout](#css-grid-layout)
  - [Flexbox Layout](#flexbox-layout)
  - [SASS/SCSS Features](#sassscss-features)
- [Folder Structure](#folder-structure)
- [How to Run the Project](#how-to-run-the-project)
- [Conclusion](#conclusion)

---

## Features Implemented

### CSS Grid Layout
1. **Home Page Layout**:
   - **Location**: The main content section on the home page.
   - **Description**: CSS Grid is used to create a multi-column layout with a sidebar and main content area. It is fully responsive and adjusts according to screen size.

2. **Gallery Section**:
   - **Location**: The gallery page.
   - **Description**: CSS Grid is utilized to display images in a uniform grid structure. The grid layout adapts to show 3, 2, or 1 columns based on the screen width.

### Flexbox Layout
1. **Header Navigation**:
   - **Location**: The header across all pages.
   - **Description**: Flexbox is used to align the logo and navigation menu horizontally. It maintains a central alignment on smaller screens.

2. **Footer Layout**:
   - **Location**: The footer across all pages.
   - **Description**: Flexbox is used to align the footer content such as social icons and copyright text. It ensures proper spacing and alignment on all devices.

### SASS/SCSS Features
1. **Variables**:
   - **Location**: Defined in the `_variables.scss` file.
   - **Description**: Variables are used for colors, font sizes, and spacing, making it easy to maintain a consistent design across the project.

2. **Custom Properties (CSS Variables)**:
   - **Location**: `global.scss`
   - **Description**: Custom properties are used to manage theming, making it easy to adjust design elements dynamically.

3. **Nesting**:
   - **Location**: Implemented throughout SASS files.
   - **Description**: SCSS nesting is used to structure the styles logically and keep related code together.

4. **Interpolation**:
   - **Location**: Used in `_typography.scss`.
   - **Description**: Dynamic class names are created using interpolation to simplify typography classes, e.g., `#{$size}-text`.

5. **Placeholder Selectors**:
   - **Location**: In `_mixins.scss`.
   - **Description**: Placeholder selectors like `%centered` are used for common reusable styles.

6. **Mixins**:
   - **Location**: Defined in `_mixins.scss`.
   - **Description**: Common styles and responsive utilities (e.g., flex centering, media queries) are stored in mixins for reuse.

7. **Functions**:
   - **Location**: Created in `_functions.scss`.
   - **Description**: Functions like `calculate-spacing()` are used to convert pixels to responsive units like `rem`.

### Additional SASS/SCSS Features
1. **Partials and Modular Structure**:
   - **Location**: Project organized into folders like `components`, `layouts`, `themes` for better maintainability.

2. **@Each Directive**:
   - **Location**: Used in `_grid.scss`.
   - **Description**: Loops over predefined sizes to dynamically generate grid classes.

3. **Dark Mode Theme**:
   - **Location**: Implemented in `themes/_dark.scss`.
   - **Description**: A dark mode theme using SASS mixins to swap between light and dark color variables.

4. **Media Query Mixin**:
   - **Location**: Created in `_mixins.scss`.
   - **Description**: A media query mixin ensures the responsiveness of fonts, layout, and elements across devices.

---

## Folder Structure

```bash
/sass
   /components
      _header.scss
      _footer.scss
      _buttons.scss
   /layouts
      _grid.scss
      _flexbox.scss
   /themes
      _light.scss
      _dark.scss
   /common
      _variables.scss
      _mixins.scss
      _functions.scss
   main.scss
