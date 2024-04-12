<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="img/favicon.png" alt="Project logo"></a>
</p>

<h3 align="center">Natours</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> Exciting tours for adventurous people
    <br> 
</p>

## 📝 Table of Contents

- [About](#about)
- [What I Learned](#what_i_learned)
- [Getting Started](#getting_started)
- [Deployment](#deployment)
- [Usage](#usage)
- [Built Using](#built_using)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>

The purpose of this project is to create a landing page for a company that sell tours packs to people.

## What I Learned 💡 <a name = "what_i_learned"></a>

During the development of this project, I explored a range of advanced CSS techniques and web development concepts, including:

- Utilization of modern CSS techniques, such as `clip-path`, `background-clip`, `background-blend-mode`, `shape-outside`, `backdrop-filter`, `object-fit`, `transform`, `perspective`, custom CSS properties and others to create stunning designs and effects;
- Implementation of advanced CSS animations with `@keyframes`, `animation`, and `transition`;
- Exploration of advanced CSS selectors, pseudo-classes, and pseudo-elements necessary for modern CSS development;
- Understanding of how CSS works behind the scenes, including concepts such as the cascade, specificity, inheritance, value processing, the visual formatting model, the box model, positioning schemes, and stacking contexts;
- Adoption of CSS architecture practices, such as the 7-1 rule, component-based design, the BEM methodology, and writing reusable, maintainable, and scalable code;
- Introduction to the Sass preprocessor, including variables, nesting, partials, imports, mixins, functions, extends, and more;
- Application of Sass in real-world projects, including setting global variables, promoting code reusability, architecting CSS, and managing media queries;
- Utilization of the NPM ecosystem to set up a development process for compiling Sass and automatically reloading the browser, and creating a build process for concatenating, prefixing, and compressing CSS files;
- Implementation of modern responsive design techniques, including fluid grids, layout types, flexible images, and the use of media queries to ensure a consistent experience across different devices;
- Adoption of advanced responsive design workflows, such as mobile-first vs desktop-first strategies, breakpoint selection, em vs rem units, and feature queries to test browser support;
- Utilization of responsive images and videos in HTML and CSS to optimize page loading times and enhance the user experience.

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

You will need to have [Nodejs](https://nodejs.org/en/) in your system.

Check the documentation to install it on your system.

### Installing

<img width=1080 height=300 src="screenshots/screenshot-1.png" alt="Project logo"></a>

Once you have Node Js on your system.

Run **npm install**

You can see in the package.json all the scripts.

```

"scripts": {
    "watch:sass": "node-sass sass/main.scss css/style.css -w",
    "devserver": "live-server",
    "start": "npm-run-all --parallel devserver watch:sass",
    "compile:sass": "node-sass sass/main.scss css/style.comp.css",
    "concat:css": "concat -o css/style.concat.css css/icon-font.css css/style.comp.css",
    "prefix:css": "postcss --use autoprefixer -b 'last 10 versions' css/style.concat.css -o css/style.prefix.css",
    "compress:css": "node-sass css/style.prefix.css css/style.css --output-style compressed",
    "build:css": "npm-run-all compile:sass concat:css prefix:css compress:css"
  },

package.json

```

## 🎈 Usage <a name="usage"></a>

You can make changes in the components inside the sass folder.
Run **npm watch:sass** to see in the browser all the changes that you do in the page.

## 🚀 Deployment <a name = "deployment"></a>

You can deploy this page to Netlify.

## ⛏️ Built Using <a name = "built_using"></a>

- [HTML](https://nodejs.org/en/) - Markup Language
- [CSS](https://nodejs.org/en/) - Stylesheets
- [SASS](https://sass-lang.com/) - CSS Preprocessor

## ✍️ Authors <a name = "authors"></a>

- [@freitasvin](https://github.com/freitasvin) - Build by
- [@jonasschmedtmann](https://github.com/jonasschmedtmann) - Idea & Initial Work

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- CSS Udemy Jonas Course
- Natours
