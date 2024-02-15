# Recipe page solution

This is a solution to the [Recipe page challenge](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

![Design preview for the Recipe page](./design/desktop-preview.jpg)


### Screenshot
- Mobile:<br/>
![Mobile View](assets/screenshots/mobile.png)
<hr/>

- Destkop:
![Desktop View](assets/screenshots/desktop.png)
<hr/>


## My process

- Start by reviewing the user's instructions and understanding what was required.
- Create a new repository in Github.
- Initialize git, create an HTML file called `index.html`.
- Set up the project structure using HTML5 semantic tags.
- Install and Add Sass in order to preprocess the css into a stylesheet.
- Add CSS stylesheet link to my html document and began writing basic styling.
- Create a responsive layout based on the provided design mock.
- Use media queries to adjust the font size and spacing accordingly.
- Add Animation to the page and main dish picture.
- Test with Chrome Lighthouse for performance, SEO and Accessibility.
- Bundle the files with Parcel in build in order to optimize and minify.
- Deploy to github pages.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Responsive design
- Sass
- ParcelJS
- Animation

### What I learned

A common mistake circling around `parcel` is that when building  a production version of your website you might face an issue where a `/` is added 
in front of all the paths to `css` or `images`.

The solution for this issue is to configure the build script in `package.json` as follows  `"scripts": {"build": "parcel build ./index.html --public-url ./",}`
then you can build by typing  `npm run build` in your terminal.

### Useful resources

- [Sass](https://sass-lang.com/) - Sass is the most mature, stable, and powerful professional grade CSS extension language in the world.
- [Parceljs](https://parceljs.org/) - Parcel combines a great out-of-the-box development experience with a scalable architecture that can take your project from just getting started to massive production application.

## Author

- Github - [Github](https://github.com/amrmabdelazeem)
- Frontend Mentor - [@amrmabdelazeem](https://www.frontendmentor.io/profile/amrmabdelazeem)
