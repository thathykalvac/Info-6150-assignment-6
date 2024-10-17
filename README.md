# Info-6150-assignment-6

This project demonstrates the use of CSS layout techniques like **CSS Grid**, **Flexbox**, and **SASS/SCSS** features to build a responsive website. The goal is to optimize CSS through modular design and ensure the layout adapts smoothly across different screen sizes.

## Table of Contents
- [Features Implemented](#features-implemented)
  - [CSS Grid Layout](#css-grid-layout)
  - [Flexbox Layout](#flexbox-layout)
  - [SASS/SCSS Features](#sassscss-features)
- [Folder Structure](#folder-structure)


---

## Features Implemented

### CSS Grid Layout
1. **Home Page**:
   - The main content section on the home page. CSS Grid is used to create a multi-column layout with a sidebar and main content area. It is fully responsive and adjusts according to screen size.

2. **Products Page**:
   - The products page is used to display the items on the sale. CSS Grid is utilized to display images in a uniform grid structure. The grid layout adapts to show columns based on the screen width.

### Flexbox Layout
1. **Header Navigation**:
   - Flexbox is used to align the logo and navigation menu horizontally. It maintains a central alignment on smaller screens.

2. **Footer Layout**:
   - Flexbox is used to align the footer content such as social icons and copyright text. It ensures proper spacing and alignment on all devices.

### SASS/SCSS Features
1. **Variables**:
   - Defined in the `_variables.scss` file. Variables are used for colors, font sizes, and spacing, making it easy to maintain a consistent design across the project.

2. **Custom Properties (CSS Variables)**:
   - used inside `_topography.scss`. Custom properties are used to manage theming, making it easy to adjust design elements dynamically.

3. **Nesting**:
   - SCSS nesting is used to structure the styles logically and keep related code together.

4. **Interpolation**:
   - Used in `_product-card.scss`. Dynamic product cards are created using interpolation .

5. **Placeholder Selectors**:
   - Used in `_product-card.scss`. Used to creating reusable styles to reduce no of lines of code.

6. **Mixins**:
   - Defined in `_mixins.scss`. Common styles and responsive utilities (e.g., flex centering, media queries) are stored in mixins for reuse.

7. **Functions**:
   - A function named rem is created in `_home.scss` function is used to define text size of header.

### Additional SASS/SCSS Features
1. **Lighten**:
   - Used in various places of code to give lighter version of a color. 

2. **String Interpolation**:
   - Used in background image URL.

3. **Import**:
   - Import is used to import scss files into main scss file


---

## Folder Structure

```bash
scss/
|-- base/
|   |-- _reset.scss        
|   |-- _typography.scss    
|
|-- components/
|   |-- _header.scss        
|   |-- _footer.scss        
|   |-- _product-card.scss   
|   |-- _contact-form.scss   
|   |-- _faq.scss           
|   |-- _founder.scss       
|
|-- layout/
|   |-- _grid.scss          
|   |-- _flex.scss          
|
|-- pages/
|   |-- _home.scss          
|   |-- _product.scss       
|
|-- themes/
|   |-- _colors.scss        
|   |-- _mixins.scss        
|
|-- main.scss               
| index.html              
| product.html            
