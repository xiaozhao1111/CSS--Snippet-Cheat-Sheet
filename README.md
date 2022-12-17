# CSS--Snippet-Cheat-Sheet

## Description
This is a webpage created with Html and CSS to hold a collection of CSS snippets.


## The layout of the webpage
The image show the layout of the webpage. The header section has a heading and a paragraph. The main section has six cards. The dispaly of six card is responsive to the device. 3 columns for large screen, 2 columns for device with a screen-width between 768px and 992px, and 1 column for device with a screen-width under 768px. At the bottom of the webpage, there is a footer.

![layout-image](/images/layout.png)


## Features
### Semantic HTML elements
Use <header> <main> <footer> semantic HTML elements to improve the accessibilty of the webpage.

### CSS variables
Set CSS variables with the code below to maintain clean and reusable values for a color scheme.
:root {
   --bright: rgb(232, 102,236);
   --dark: rgb(0,0,0);
}

### Responsive grid layout
Use CSS grid and media queries to create a responsive grid layout.

### Copy code from the card
Each CSS snippet can easily be highlighted for copying on click using the CSS user-select property.

### Animation
When the cursor moves on the card, the card will become larger with color box shadows.


## Deployed webpage
https://xiaozhao1111.github.io/CSS--Snippet-Cheat-Sheet/