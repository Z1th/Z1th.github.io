---
title: "My Own Portfolio"
description: "I have wanted to have my own portfolio to share with my friends for a long time, and now I have finally achieved it! I am really excited to have been able to create it."
pubDate: "Apr 23 2023"
heroImage: "/myFirstPortfolio.webp"
badge: "#HTML #CSS #ASTRO"
---

<b>General description</b>
<br>
This project was born with the goal of having a place where I can constantly update my work and easily share it.

The website uses the architecture of AstroIsland where each component is separated individually and later loaded by calling them from an index. Astro allows this website to function quickly and offers support in code reuse for various pages within the site.

The main objectives of this site are to be fast, have an easy user interface, and allow you to easily find what you are looking for.

<b>Stack used</b>
<ul>
<li>HTML</li>
<li>CSS</li>
<li>Astro</li>
<li>Tailwind</li>
<li>DaisyUI</li>
</ul>

<b>Project Structure</b>
```php
├── src/
│   ├── components/
│   │   ├── cv/
│   │   │   ├── TimeLine.astro
│   │   │   ├── SkillsTeach.astro
│   │   ├── BaseHead.astro
│   │   ├── Card.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   └── HorizontalCard.jsx
│   │   └── SideBar.jsx
│   ├── content/
│   │   ├── blog/
│   │   │   ├── helloworld.md
│   │   ├── project/
│   │   │   ├── hacklatino.md
│   │   │   ├── myownportfolio.md
│   │   │   ├── octopus.md
│   │   │   ├── umaeeforall.md
│   │   │   ├── umaeeMail.md
│   │   │   ├── umaeeNetflixMockUp.md
│   │   ├── store/
│   │   │   ├── item1.md
│   │   │   ├── item2.md
│   ├── layouts/
│   │   └── BaseLayout.astro
│   │   └── ProjectLayout.astro
│   │   └── PostLayout.astro
│   └── pages/
│   │   ├── blog/
│   │   │   ├── [...page].astro
│   │   │   ├── [slug].astro
│   │   ├── project/
│   │   │   ├── [...page].astro
│   │   │   ├── [slug].astro
│   │   └── cv.astro
│   │   └── index.astro
│   │   └── projects.astro
│   │   └── 404.astro
│   │   └── services.astro
│   │   └── rss.xml.js
│   └── styles/
│       └── global.css
├── public/
├── astro.config.mjs
├── tailwind.config.cjs
├── package.json
└── tsconfig.json
```

<b>Components usage</b><br>
This website features BaseHead, Footer, Header, and Sidebar layout components. These components manage all the content within the website.

<b>Sidebar</b><br>
The sidebar section includes the entire sidebar where you can edit your profile picture, as well as all the links to the different available sections within the portfolio. At the bottom, there is also a list of links that lead to various social media networks.
<br>

<b>Content</b><br>
Here is where all the text content of the website, project documentation, and blog posts are stored.

<b>Layouts</b><br>
This is the skeleton of the website where the schemas created from the ./content/config.ts file are called, in these schemas the collections of the elements that each of the components will have are declared and later exported.

<b>Pages</b><br>
Blog uses Astro's content collection to query post's md.

[page].astro
The [page].astro is the route to work with the paginated post list.

[slug].astro
The [slug].astro is the base route for every blog post.

The other pages are static pages. The index page belong to the root page.

<b>Deploy information</b><br>
This website is hosted on Github pages following the specific documentation of <a href="https://docs.astro.build/en/guides/deploy/github/" target="_BLANK">Astro.build for Github pages</a>.

<h2><b>This website meets all the optimizations!</b></h2>
<img src="/rendimientoWebsite.webp">
<a href="https://pagespeed.web.dev/analysis/https-z1th-github-io/8kg5z9tvs2?hl=es-419&form_factor=mobile">Try it yourself</a>
<!-- Insertar video aquí-->