# tiyeni-app.github.io

0. Continue - [To Access Tiyeni.App](https://tiyeni-app.github.io/public/)

This is the template for Tiyeni.app (no frameworks) with Tailwind CSS setup. You only need to install Node.js to have access to NPM.

Follow the steps.
## Getting Started

1.  Download and install NODE - [To access npm-Node Package Manager](https://nodejs.org/en/)

2.  Install dependencies from the terminal of the folder of this fetched repo

        npm install

3.  Build using Tailwind CSS

        npm run build

4.  Open the `public > index.html` and you should see the Tiyeni website running. Retrace the steps if you dont see anything working.

## How to use

- Go to `public > index.html` and start edititng the HTML.
- If you need to add more HTML pages, add them in the `public` folder.

- Edit the custom CSS file in `input.css`. Add any amount of custom CSS within this file. Refer [https://tailwindcss.com/docs/adding-custom-styles#using-css-and-layer]

Watch HTML files for changes and build automatically everytime using
## keep this command running on the terminal in root folder to sync changes during development

    npm run watch

NOTE: Do NOT edit the file `public > dist > styles.css` directly - This is the distribution stylesheet. The CSS here is generated from `src > styles.css` using Tailwind when you build.

## To optimize for production

Before pushing your code (the `public` folder) for production, run the below command to reduce the size of `styles.css` within the public folder

     npm run prod

NOTE: If you are using Windows and face an error `NODE ENV not recognised`, run the below command

     npm install win-node-env


