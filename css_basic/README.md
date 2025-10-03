CSS Basics Project

This project is part of the ALX Software Engineering Program. It builds upon the html_basic project and introduces CSS styling, Flexbox layout, and responsive design concepts.

📂 Repository Structure

GitHub repository: alx_html_css

Directory: css_basic/

Files included:

index.html

tweets.html

base.css (provided base styles)

styles.css (custom styles written for the tasks)

✅ Requirements

All files end with a new line

A README.md file is present

No external libraries (no NodeJS, React, VueJS, Bootstrap, etc.)

Only HTML and CSS used

Code validates with W3C Validator

🚀 Tasks Completed
0. Some early styling

Created directory css_basic in alx_html_css

Copied index.html and tweets.html from html_basic

Added base.css (provided) and empty styles.css

Linked both CSS files inside the <head> of each HTML file

✅ Check:

Open index.html or tweets.html in the browser → basic styles applied

1. Positioning

Implemented Flexbox layout

<body> is a flex container with flex-direction: column

<main> is a flex container with flex-direction: row

<article> takes 2/3 width (flex: 2)

<aside> takes 1/3 width (flex: 1)

Both <article> and <aside> are scrollable with overflow-y: auto

✅ Check:

Open index.html → layout shows:

Header

Article + Aside side-by-side

Footer

2. Responsive Web Design

Added class="works_on_smartphone" to <body> in index.html

Confirmed responsive rules in base.css handle small screens

Added viewport meta tag:

<meta name="viewport" content="width=device-width, initial-scale=1.0">


✅ Check:

Resize browser → layout collapses to single column

Open on mobile / device emulator in Chrome → proper scaling, no zoomed-out view

3. Some more styling

Customized styling in styles.css (colors, backgrounds, borders, etc.)

Added a simple logo (Unicode character) as first <li> in <header> with class="logo"

✅ Check:

Open index.html → see unique styles

Header shows logo character

🔍 How to Validate

Clone the repository:

git clone https://github.com/Sirumba/alx_html_css.git
cd alx_html_css/css_basic


Open index.html and tweets.html in a browser

Inspect elements to confirm Flexbox layout and responsive design

Run code through W3C Validator
 to check compliance

🌐 Links

Repo: alx_html_css

Directory: css_basic/