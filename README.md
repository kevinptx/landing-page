# Landing Page Project

Landing Page Project for Udacity's [Front End Developer Nanodegree](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd0011)

## Table of Contents

* [Description](#description)
* [Instructions](#instructions)
* [Project Structure](#project-structure)
* [Usage](#usage)
* [Credits](#credits)

## Description

This project is a simple landing page that demonstrates the use of JavaScript to manipulate the DOM. It also showcases responsive design techniques using HTML and CSS.

## Instructions

To get started, clone the project to your local machine and open the `index.html` file in your browser.

## Project Structure

The project contains the following files and folders:

```bash
landing-page/
├── README.md
├── index.html
├── css/
│   └── styles.css
└── js/
    └── app.js
```

- `README.md`: Contains the documentation for the project
- `index.html`: Contains the HTML structure of the landing page
- `css/`: Contains the CSS styles for the landing page
- `js/`: Contains the JavaScript code that dynamically creates the navigation menu, scrolls to the appropriate section, and highlights the section and corresponding link when in view.

## Usage

This landing page can be used as a general template for a variety of purposes. 
The navigation menu is dynamically constructed based on the number of sections in the HTML file. Clicking on a navigation menu item will smoothly scroll to the corresponding section on the page. The currently active section in the viewport will be highlighted in both the navigation menu and on the page. Additionally, a "To Top" button will appear when the user scrolls down the page, allowing them to quickly return to the top of the page. 

This script provides the following features:

- Dynamically builds a navigation menu based on the sections in the document.
- Scrolls to the appropriate section when a navigation link is clicked.
- Highlights the current section in the navigation menu as the user scrolls through the page.
- Shows/hides a "to top" button depending on the user's scroll position, and scrolls to the top of the page when the button is clicked.

To use this script in your project, simply include the JavaScript file and initialize the NavigationMenu object. You can customize the appearance and behavior of the menu by modifying the CSS styles and the configuration options in the JavaScript file.

## Credits

This project was created by [Kevin Peery](https://www.linkedin.com/in/kevin-peery/) for Udacity's Front End Developer Nanodegree program. 
