# EJS-Partials

This project showcases a simple web application built using Node.js, Express, and EJS (Embedded JavaScript Templates) for rendering dynamic HTML pages. The application consists of an index.js file, multiple EJS templates (index.ejs, about.ejs, contact.ejs, and footer.ejs), and a header.ejs file for the website's header section.

## Files and Functionality

1. **index.js**: This file serves as the main entry point for the server. It sets up an Express application, configures a static file server for serving assets from the "public" directory, and defines routes for the home page ("/"), "About" page ("/about"), and "Contact" page ("/contact"). The server listens on port 3000.
2. **index.ejs**: The home page template. It includes the partials/header.ejs and partials/footer.ejs files, along with some placeholder text and Lorem Ipsum content.
3. **about.ejs**: The "About Me" page template. It also includes the partials/header.ejs and partials/footer.ejs files, along with some placeholder text and Lorem Ipsum content.
4. **contact.ejs**: The "Contact Me" page template. It includes the partials/header.ejs and partials/footer.ejs files, along with a simple contact form.
5. **footer.ejs**: A reusable footer template that contains social media icons, a navigation menu, a copyright notice, and a wave animation effect.
6. **header.ejs**: A reusable header template with a navigation bar that collapses on smaller screens. It includes the website logo, a hamburger menu, and links to different pages.

## Dependencies

This project relies on the following dependencies:

1. Express: A web application framework for Node.js.
2. EJS: A templating engine for Node.js that allows for dynamic HTML rendering.
3. Ionicons: A set of open-source web-friendly interface icons.

## Usage

To run this project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies by running `npm install` in the project directory.
3. Start the server by running `node index.js` or `npm start`.
4. Open your web browser and visit `http://localhost:3000` to access the website.

This project demonstrates how to use EJS templates and partials to create a reusable and modular web application. It also showcases the integration of a simple contact form and a responsive header with collapsible navigation.
