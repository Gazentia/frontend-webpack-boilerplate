<div id="top"></div>
<div align="center">
  <a href="https://github.com/Gazentia/frontend-webpack-boilerplate">
<img src="./readme-assets/banner.jpg" align="center"/>
  </a>
  <br/>
  <br/>
  <p align="center">
    <a href="https://github.com/Gazentia">About Me</a>
    ·
    <a href="https://github.com/Gazentia/frontend-webpack-boilerplate/issues">Report Bug</a>
    ·
    <a href="https://github.com/Gazentia/frontend-webpack-boilerplate/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#aboutProject">About The Project</a>
      <ul>
        <li><a href="#builtWith">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#gettingStart">Getting Started</a>
      <ul>
        <li><a href="#preparing">Prerequisites</a></li>
        <li><a href="#install">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#build">Build a project</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

<div id="aboutProject"></div>

## About The Project

This is my starter frontend webpack boilerplate for web development.

Here's why:

- Reducing DRY for starting new project structure from scratch.
- Make sure that the template can make template that support almost browser.
- Getting a conveniently structure pattern for organizing sass files.
- Practicing Web development skills.

<p align="right">(<a href="#top">back to top</a>)</p>

<div id="builtWith"></div>

### Built With

The list of major Webpack plugins and loaders that i have used for building this template.

- [Webpack](https://webpack.js.org/)
- [Babel](https://github.com/babel/babel)
- [Autoprefixer](https://github.com/postcss/autoprefixer#webpack)
- [Babel loader](https://www.npmjs.com/package/babel-loader)
- [Sass loader](https://github.com/webpack-contrib/sass-loader)
- [Postcss loader](https://www.npmjs.com/package/postcss-loader)
- [File loader](https://github.com/webpack-contrib/file-loader)
- [Html Webpack Plugin](https://webpack.js.org/plugins/html-webpack-plugin/)
- [Favicons Webpack Plugin](https://github.com/jantimon/favicons-webpack-plugin)
- etc.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

<div id="gettingStart"></div>

## Getting Started

<div id="preparing"></div>

<b>Downloading and installing [Node.js](https://nodejs.org/en/) first.</b></br>

<div id="install"></div>

### Installation

You can install and start using the template with these steps :

1. Clone the repo
   ```sh
   git clone https://github.com/Gazentia/frontend-webpack-boilerplate.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Starting Live Server and then you can look at [localhost:8080](http://localhost:8080/)
   ```sh
   npm run start:dev
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE -->
<div id="usage"></div>

## Usage

In this section i will explain about the structure project that you will work with them.

```
Project (In src/ folder)
│   index.html
│
└─── assets
│   └─── fonts
│   └─── images
│   └─── js
│       │   app.js
│       │   main.js
│       │   polyfill.js
│       │   vendor.js
│   └─── sass
│       │   main.scss
│       └─── abstracts
│       └─── base
│       └─── components
│       └─── layout
│       └─── pages
│       └─── themes
│       └─── vendors
```

### New Page (Html files)

- Create your new file at the root of `src` directory ( in the same directory as `index.html`).

### `JS` FOLDER

- `app.js` : javascript code that working with your page.
- `main.js` : the entry point file for javascript and scss.
- `polyfills.js` : the entry point file for other polyfill.
- `vendor.js` : the entry point file for other vendor.

### `SASS` FOLDER (7-1 SASS Architecture)

- `main.scss` : the entry point for <b>Only</b> importing the other scss files.
- `abstracts` : contains Sass tools, helper files, variables, functions, mixins and other config files.
- `base` : contains the boilerplate code and standard styles such as resets and typographic rules.
- `components` : contains all of your styles for buttons, carousels, sliders, and similar page components.
- `layout` : contains all styles involved with the layout of your project.
- `pages` : contains any styles specific to individual pages.
- `themes` : contains files that create project specific themes.
- `vendors` : contains all third party code from external libraries and frameworks.

### `IMAGES` FOLDER

- Containes all any image, icon, svg files.
- `favicon.png` : a favicon file.
- If you want to refer svg file with `src` you can do it by using `<%=require('_your_svg_path_')%>` such as `<img src="<%=require('./assets/images/logo.svg')%>" alt="" />`

### `FONTS` FOLDER

- Containes all font files (default i used [Prompt](https://fonts.google.com/specimen/Prompt) font family).
- You can config your new font family at `src/base/_typography.scss` .

<div id="build"></div>

## Build a project

You can build your project with production mode:

```sh
npm run build
```

You can build your project with development mode:

```sh
npm run build:dev
```

<p align="right">(<a href="#top">back to top</a>)</p>

## Gazentia

```
Thank you for your attention. I'm willing listen your suggestions.
```

