---
layout: post
title:  "From This Day Forth"
tech: "React, GatsbyJS"
date:   2017-11-21 20:23:15 +0000
---
From This Day Forth is a website for a friend who is an excellent [Humanist Celebrant](https://www.humanism.ie/). You can view the website [here](https://fromthisdayforth.ie/)

As this client may want a blog in the future, I decided to use [Gatsby JS](https://www.gatsbyjs.org/).
I know that when most people think blogs they think Wordpress.

I'm against Wordpress for a few reasons:

- Poor security
- Having to use aging PHP
- Old school and slow at times
- Non-optimized code
- Hosting can be a pain

Gatsby JS is the new kid on the block and getting a lot of attention in the SSG community. Reasons I like Gatsby JS:

- Uses the latest tools: React, Webpack and GraphQL under the hood
- Static Site Generation, no need for a CMS
- Blogs can be written in Markdown
- Extremely fast, generates minimal HTML, CSS and JavaScript

As the code is all static content: HTML; CSS; JavaScript. I had plenty of free options when it came to hosting. I decided
to use Firebase Hosting. They automatically push the code to their global CDN, give each website their own free SSL certificate using
Let's Encrypt and have a nice simple cli for deployments.

For the Contact Page, I created a simple NodeJS/ExpressJS API that would email my client when a customer was interested in their product.