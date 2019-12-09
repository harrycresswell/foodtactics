# Hugo Starter 1.0

## Features

- [Hugo](https://gohugo.io/)
- [Hugo pipes](https://gohugo.io/hugo-pipes/) for SCSS and JS
- Autoprefixer
- [Lazysizes.js](https://github.com/aFarkas/lazysizes) for image lazy loading
- Sourcemaps for local development
- Netlify Large Media
- Minimal dependencies


## Prerequisites

You need to have the latest/LTS [node](https://nodejs.org/en/download/) and [npm](https://www.npmjs.com/get-npm) versions installed in order to use Victor Hugo.

## Installation

Clone this repository 

```
git clone ...
```
then run `npm install`.

This will install the necessary dependencies.

## Local development

```
npm start
```
This will start a local development server at https://localhost:1313/ in the browser. It’s shorthand for `hugo server --disableFastRender`.


## Production build

```
Hugo
```

## Basic concepts

A few of the basic concepts to get the most out of using this theme.

### Adding Content

Create a new markdown file in the posts directory:

```
hugo new post/my-new-post.md
```

Create a new page in the page directory:

```
hugo new page/my-new/page.md
```

### Writing Sass

Write your **Sass** inside `./assets/scss`. 

With the server running (`npm start`) Hugo will watch your Sass for changes, then pipe them to `./public/css/main.css` and reload the browser.


