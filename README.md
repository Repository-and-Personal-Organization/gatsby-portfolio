<p align="center">
  <a href="https://cara.lekoarts.de">
    <img alt="LekoArts" src="https://img.lekoarts.de/gatsby/gatsby-site-illustration.png" />
  </a>
</p>
<h1 align="center">
  Gatsby Starter Portfolio
</h1>

<p align="center">
  <a href="https://github.com/LekoArts/gatsby-starter-portfolio-cara/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-0BSD-blue.svg" alt="Gatsby Starter Portfolio: Cara is released under the 0BSD license." />
  </a>
  <a href="https://estevam.gatsbyjs.io/">
    <img alt="Website" src="https://img.shields.io/badge/-website-blue">
  </a>
</p>

Playful and Colorful One-Page portfolio featuring Parallax effects and animations. Using the Gatsby Theme [`@lekoarts/gatsby-theme-cara`](https://github.com/LekoArts/gatsby-themes/tree/main/themes/gatsby-theme-cara).

[![Live Preview](https://img.lekoarts.de/gatsby/preview.svg)](https://estevam.gatsbyjs.io/)

<!-- Also be sure to check out other [Free & Open Source Gatsby Themes](https://themes.lekoarts.de) and my [Personal Website](https://www.lekoarts.de?utm_source=cara&utm_medium=Starter). -->

## ✨ Features

- Theme UI-based theming
- react-spring Parallax Effect
- CSS Animations on Shapes

### 1. **Create a Gatsby site.**

Use `git` to clone the site and navigate into it:

```sh
git clone https://github.com/Estevamsl/gatsby-portfolio
cd gatsby-portfolio
```

### 2. **Install dependencies.**

If you use npm 7 or above use the `--legacy-peer-deps` flag. If you use npm 6 you can use `npm install`.

```sh
npm install --legacy-peer-deps
```

### 3. **Open the code and start customizing!**

Start the site by running `npm run develop`.

Your site is now running at `http://localhost:8000`!

If you want to learn more about how you can use a Gatsby starter that is configured with a Gatsby theme, you can check out this [shorter](https://www.gatsbyjs.com/docs/how-to/plugins-and-themes/using-a-gatsby-theme/) or [longer](https://www.gatsbyjs.com/tutorial/using-a-theme/) tutorial. The tutorials don't exactly apply to this starter however the concepts are the same.

![Programmer Logo](video/gatsbyVideo.gif)

## Usage

### Theme options

| Key        | Default Value | Description                                                                                             |
| ---------- | ------------- | ------------------------------------------------------------------------------------------------------- |
| `basePath` | `/`           | Root url for the theme                                                                                  |
| `mdx`      | `true`        | Configure `gatsby-plugin-mdx` (if your website already is using the plugin pass false to turn this off) |

#### Example usage

```js
// gatsby-config.js
module.exports = {
  plugins: [
    {
      resolve: `@lekoarts/gatsby-theme-cara`,
      options: {
        // basePath defaults to `/`
        basePath: `/sideproject`,
      },
    },
  ],
};
```

#### Additional configuration

In addition to the theme options, there are a handful of items you can customize via the `siteMetadata` object in your site's `gatsby-config.js`

```js
// gatsby-config.js
module.exports = {
  siteMetadata: {
    // Used for the title template on pages other than the index site
    siteTitle: `Cara`,
    // Default title of the page
    siteTitleAlt: `Cara - @lekoarts/gatsby-theme-cara`,
    // Can be used for e.g. JSONLD
    siteHeadline: `Cara - Gatsby Theme from @lekoarts`,
    // Will be used to generate absolute URLs for og:image etc.
    siteUrl: `https://cara.lekoarts.de`,
    // Used for SEO
    siteDescription: `Playful and Colorful One-Page portfolio featuring Parallax effects and animations`,
    // Will be set on the <html /> tag
    siteLanguage: `en`,
    // Used for og:image and must be placed inside the `static` folder
    siteImage: `/banner.jpg`,
    // Twitter Handle
    author: `@lekoarts_de`,
  },
};
```

## 📝 Using and modifying this starter

**Important Note:** Please read the guide [Shadowing in Gatsby Themes](https://www.gatsbyjs.com/docs/how-to/plugins-and-themes/shadowing/) to understand how to customize the underlying theme!

This starter creates a new Gatsby site that installs and configures the theme [`@lekoarts/gatsby-theme-cara`](https://github.com/LekoArts/gatsby-themes/tree/main/themes/gatsby-theme-cara).

Have a look at the theme's README and files to see what options are available and how you can shadow the various components including Theme UI. Generally speaking you will want to place your files into `src/@lekoarts/gatsby-theme-cara/` to shadow/override files. The Theme UI config can be configured by shadowing its files in `src/gatsby-plugin-theme-ui/`.

### Changing content

The content of this project is defined in four `.mdx` files inside the theme's `sections` folder. You can override the files `intro.mdx`, `projects.mdx`, `about.mdx` and `contact.mdx`. This starter has overridden all files for you already.

You have to use the `<ProjectCard />` component inside `projects.mdx` to display the cards. Example:

```md
## Projects

<ProjectCard title="Freiheit" link="https://www.behance.net/gallery/58937147/Freiheit" bg="linear-gradient(to right, #D4145A 0%, #FBB03B 100%)">
This project is my entry to Adobe's #ChallengeYourPerspective contest.
</ProjectCard>
```

### Change your `static` folder

The `static` folder contains the icons, social media images and `robots.txt`. Don't forget to change these files, too! You can use [Real Favicon Generator](https://realfavicongenerator.net/) to generate the image files inside `static`.

## 🚀 Getting Started

[<img src="https://www.gatsbyjs.com/deploynow.svg" alt="Deploy to Gatsby Cloud">](https://www.gatsbyjs.com/dashboard/deploynow?url=https://github.com/LekoArts/gatsby-starter-portfolio-cara)
