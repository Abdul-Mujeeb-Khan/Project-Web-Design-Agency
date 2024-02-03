# **Web Design Agency Frontend Project Documentation**

# **Project Overview**

### **Project Name:**

SparkSphere

### **Project Description:**

This website is based on pure HTML and CSS without using any frameworks. The goal of this website is to demonstrate the power of responsiveness that can be achieved using pure HTML and CSS. The features include dynamic and responsive design with minimalistic approach.

### Technologies Used:

- HTML
- CSS

## Project Structure:

### Files and Directories:

- **index.html:** Main HTML file
- **styles.css:** Main CSS file
- **normalize.css:** Providing basic default styles for some HTML elements to look consistent over different browsers
- **components/:** Directory **s**howcasing different components used in this project
- **images/:** Directory for project images
- **fonts/:** Directory for project fonts
- **scripts/:** Directory for JavaScript files (if applicable)

### **Dependencies:**

No third-party libraries as in frameworks, were used in building this project.

For Fonts [fonts.google.com](http://fonts.google.com) is used. Font style - Inter has been used, which is imported through DNS of the website, not imported locally.

JavaScript dependency AOS was used for Animations.

## **Design Mockups:**

[Include screenshots or links to design mockups for reference.]

## **Features:**

1. Made using only HTML and CSS
2. BEM (Block Element Modifier) implementation
3. CSS Best practices used for efficiency such as separation of concerns
4. Semantic HTML used for SEO
5. DRY (Don’t Repeat Yourself) implementation
6. Object-Oriented CSS used
7. CSS Variables used for Custom Properties
8. Transformations and transitions used for a Dynamic Frontend
9. Image Sprites for Better performance and reduced HTTP requests
10. Responsive on different devices
11. Minimalistic approach

## **Development Process:**

- The Development process begins with inherent challenges, the first of which is identifying different styles and the components to be used, derived from the design mockup.
- The next step was to decide the color palette, so as the design looks consistent.
- Committing changes to the GitHub Repository is another crucial task so as to maintain development history of the project.
- Next, is setting up Typography, the fonts to be used in this project. Decided to use the font style Inter which was imported from [fonts.google.com](http://fonts.google.com) through the DNS service, not importing locally.
- Made the Website using Mobile First Approach. Then applying media queries for the desktop style into different component so as to make further changes easy.
- Made the stylesheet such that the structure and skin of each component is implemented separately such as the badge’s structure and its skin i.e. color is defined separately.
- Used Image sprites to reduce number of HTTP requests sent to server for better and enhanced performance.
- Buttons were also designed using BEM and hovering and other states were implemented.
- One of the problems faced was making the website responsive and resolved it using grid and flex-boxes.
- Used Block level structure to make the website.
- Used HTML and CSS validator for optimization.
- Added Meta tags a part of SEO.

## **HTML Structure:**

[Outline the structure of the HTML document, including the main sections and elements used.]

```html
htmlCopy code
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Web Design Agency</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <!-- Header Section -->
    <header>
      <!-- Header content goes here -->
    </header>

    <!-- Main Content Section -->
    <main>
      <!-- Main content goes here -->
    </main>

    <!-- Footer Section -->
    <footer>
      <!-- Footer content goes here -->
    </footer>
  </body>
</html>
```

## **CSS Styles:**

[Outline the main styles and CSS rules used in the project.]

```css
cssCopy code
/* Reset CSS */
/* General styles */
/* Header styles */
/* Main content styles */
/* Footer styles */
/* Media queries for responsiveness */

```

## **Testing:**

For testing the scalability and efficiency of website, used Chrome Dev Tools and networks.

## **Deployment:**

Deployed using Github pages.

## **Conclusion:**

This project gave me an insight into the complete process of building and deploying production level website.
