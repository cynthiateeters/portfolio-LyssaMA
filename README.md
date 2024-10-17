# Portfolio - Starter Files

## Original Project

This repo was originally created by [Kevin Powell](https://kevinpowell.co) to make a personal blog site for the [Codementor](https://www.codementor.io/) DevProjects Challenge, [Create a fast and secure blog using Jamstack](https://www.codementor.io/projects/web/create-a-fast-and-secure-blog-using-jamstack-c93coupnxb).

According to Kevin at the time, "You are free to use them however you want to get started with the challenge, if you'd like to start working on creating the site without worrying about the content itself."

## File Structure

The package.json file defines the 11ty and other dependent modules used to build the site.

The `src` folder contains files so that you can get your project up and running. That folder contains:

- The Nunjucks file index.njk defines the body for the main page
- Nunjucks files in the `_includes` folder to use as a base for the different page layouts.
- Sass files for styling the pages
- 3 portfolio articles in the `portfolio` folder
- images and a logo in the `assets` folder

The articles are written in Markdown, and include Front Matter. It is possible that you will have to modify these a little if you wish to use them.

## Original Tutorial

You are not using Netlify CMS for this project - Netlify no longer supports their CMS.

With that in mind, you can [watch this video](https://youtu.be/4wD00RT6d-g) to see how Kevin used Eleventy, Netlify, and Netlify CMS to create a full-featured blog site built entirely with static files.


## My Projects

### Poem Site

The code is located in the `src` folder and the page is created in the `public` folder.

The `settings.json` in the `.vscode` folder sets the `LiveServer` configuration to serve from the `public` folder and can be used to serve the built page.

The build process includes minifying and autoprefixing of styles via the `postbuild` script, which runs automatically after a `build`.

#### Installation

**`npm install`**

> Run this command once to install the needed node modules.

#### Development Scripts

**`npm start`**

> This script runs 11ty with hot reload and serves at the URL localhost:8080. It will reload whenever there are HTML or Sass changes.

**`npm run build`**

> This script does a production build and includes minified, autoprefixed CSS. Use this as the "Publish command" if needed by hosting services such as Netlify.

#### Resources

<small>The starter was inspired by [11ty Sass Skeleton](https://github.com/5t3ph/11ty-sass-skeleton) by [@5t3ph](https://twitter.com/5t3ph)</small>

#### Remembered

This is a simple web page that displays the poem "Remembered" by Paul Laurence Dunbar. It features a styled layout, including an image of a dove that matches the essence of the poem. The design incorporates custom CSS and uses a Google font for typography. Additionally, there is a favicon image of a feather, capturing the aura of the literature.

##### Features

- **Poem**: The poem by Paul Laurence Dunbar is styled to emphasize its message.
- **Image**: An image of a dove complements the theme of the poem.
- **Responsive Design**: The page is designed to be responsive across different devices.

##### Credits

- **Poem**: "Remembered" by Paul Laurence Dunbar. [Source](https://www.public-domain-poetry.com/poems/remembered)

---

### Color Project - CodePen

#### Color Project

- **Link**: [View CodePen Project](https://codepen.io/LyssaMA/pen/GRVrVqo)
- **Description**: This project demonstrates interactive design and functionality, showcasing my coding skills and creative approach.

---

### Design Project - Figma

#### Figma Design

- **Link**: [View Figma Design](https://www.figma.com/design/vI2aNCYYgSwbngzFxwxDNr/road-less-traveled?node-id=4-10&node-type=FRAME&t=dsNSXE52Iw3ynhsL-0)
- **Description**: A design mockup showcasing a user interface concept, demonstrating my design capabilities and understanding of user experience.

---