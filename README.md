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
  <a href="https://github.com/sponsors/LekoArts">
    <img alt="GitHub Sponsors" src="https://img.shields.io/github/sponsors/LekoArts">
  </a>
  <a href="https://estevam.vercel.app">
    <img alt="Website" src="https://img.shields.io/badge/-website-blue">
  </a>
  <a href="https://twitter.com/estevamSouza199?t=2jTVetjPwI9Nz3CLY3VmBg&s=08">
    <img src="https://img.shields.io/twitter/follow/lekoarts_de.svg?label=Follow%20@lekoarts_de" alt="Follow @estevamSouza199" />
  </a>
</p>

Playful and Colorful One-Page portfolio featuring Parallax effects and animations. Using the Gatsby Theme [`@lekoarts/gatsby-theme-cara`](https://github.com/LekoArts/gatsby-themes/tree/main/themes/gatsby-theme-cara).

[**Demo Website**](https://estevam.vercel.app)

<!-- Also be sure to check out other [Free & Open Source Gatsby Themes](https://themes.lekoarts.de) and my [Personal Website](https://www.lekoarts.de?utm_source=cara&utm_medium=Starter). -->

## ✨ Features

- Theme UI-based theming
- react-spring Parallax Effect
- CSS Animations on Shapes

### 1. **Create a Gatsby site.**

Use `git` to clone the site and navigate into it:

```sh
git clone https://github.com/LekoArts/gatsby-starter-portfolio-cara project-name
cd project-name
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