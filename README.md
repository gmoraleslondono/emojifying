# emojifying

This application allows the user to click over a card to select a color. Then the program changes the background of the page based on the color/card selected.

The application combines HTML, CSS, and JavaScript to create an interactive color swatch display using Vue.js. It demonstrates the use of Vue.js components, data binding, and event handling to create dynamic and responsive web applications.

## Code Explanation:

### HTML Structure: 
The HTML structure follows the standard format for a webpage, with <html>, <head>, and <body> tags.
Inside the <head> section, various meta tags and external stylesheets are linked. These include a CSS reset stylesheet, custom CSS stylesheets, and a Google Fonts stylesheet.
The <style> section in the <head> of the HTML code contains CSS rules that define the visual appearance and layout of elements on the webpage.  It uses the grid to display the cards ordered and keep responsiveness.In the root of the style, there is a variables list with all hex colors available. Using the @keyframes the bounce animation is added to the emoji when a card is selected.
The main content of the webpage is contained within the <body> section.

### Vue Component - Swatch:
The "swatch" component defines the structure and behavior of each color swatch displayed on the page. When the user clicks over a card it sets that element to active and in consequence it triggers the page background effect.
The template section contains HTML markup for each swatch, including the emoji icon and color label.
The methods section defines a method called "corrected_color" that adjusts the text color based on the background color of the swatch, the active method, and the gradient method.

### Emojis folder:
It contains all the assets/emojis used in the application in the PNG format.
