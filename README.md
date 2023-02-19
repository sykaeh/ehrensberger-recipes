# Ehrensberger Recipe Book

Ehrensberger Recipe Book is a simple digital recipe book for the recipes of the Ehrensberger family. Built on top of [Eleventy Recipe Book](https://github.com/footedesign/Eleventy-Recipe-Book), [Eleventy Starter Boilerplate](https://github.com/ixartz/Eleventy-Starter-Boilerplate) utilizing [Eleventy](https://www.11ty.dev).

The recipe book is available [here](https://recipes.ehrensberger.org).

## Getting Started

Before you get started, make sure you have [Node.js](https://nodejs.org) installed. We recommend using
[nvm](https://github.com/nvm-sh/nvm) and making sure that you use the version specified in [.nvmrc](.nvmrc).

Run the following command in your local environment:

```
npm install
```

Then, you can run locally in development mode with live reload:

```
npm run dev
```

Open http://localhost:8080 with your favorite browser to see your digital recipe book.

## Production build

You can see the results locally in production mode with:

```
npm run serve
```

The generated HTML and CSS files are minified.

You can create an optimized production build with:

```
npm run build
```

Now, your recipe book is ready to be deployed. All generated files are located in the `_site` folder, which you can deploy with any hosting service.

## Deploy to Netlify

Clone this repository to your own GitHub account and deploy to Netlify:

[![Netlify Deploy button](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/sykaeh/ehrensberger-recipes)

## License

Licensed under the MIT License, Copyright © 2020 - present

See [LICENSE](LICENSE) for more information.
