This is my 1st project and I just learn about html and css hope you like

# Google Homepage Clone Project

This is a simple front-end project where I have created a clone of the Google Homepage. I built this project from scratch to practice basic web development concepts, focusing on how to align elements, group tags, and style a web page using HTML and CSS.

## Features Implemented
* Top Header Bar: Contains links like "About" and "Store" on the left, and "Gmail" and "Images" on the right.
* Google Logo: Created using text and colored letter by letter using CSS.
* Search Box & Buttons: Centered search input box with rounded corners and two action buttons underneath.
* Bottom Footer: A fixed footer containing links like "Advertising", "Business", "Privacy", and "Terms".

##  Tech Stack Used
* HTML: For creating the structure of the page.
* CSS: For styling colors, fonts, spacing, and page layout.

##  Key Coding Concepts Learnt & Used

### 1. Flexbox Layout (`display: flex`)
I used Flexbox to easily design the navigation bars. By turning on `display: flex` for the top navigation box, all links automatically came into a single row. I used `margin-left: auto;` on the right-side box to cleanly push the Gmail and Images links to the far right side of the screen.

### 2. Difference Between Div and Span
* `<div>` (Block Container): I used `<div>` tags to separate my page into three main boxes: the top nav bar, the main search section, and the bottom footer. Each div starts on a new line.
* `<span>` (Inline Text): I used `<span>` tags inside the Google logo text. This allowed me to target individual letters and give them separate colors (Blue, Red, Yellow, Green) without breaking the word into new lines.

### 3. Fixed Footer (`position: fixed`)
To keep the footer strictly at the bottom of the screen just like the real Google website, I used `position: fixed` along with `bottom: 0`. This makes sure the footer stays locked to the bottom edge of the browser window.

##  File Structure & How to Run
To run this project, make sure both files are saved in the exact same folder:
1. `index.html` (Your HTML structure code)
2. `style.css` (Your design rules)
