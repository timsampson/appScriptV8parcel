# Apps Script Template with Bootstrap 5 and Parcel [![clasp](https://img.shields.io/badge/built%20with-clasp-4285f4.svg)](https://github.com/google/clasp)

[Example Site URL](https://script.google.com/macros/s/AKfycbwZdZj7GoKXU2gEzTmdwt1DCLDouSG2FxNN_eu8b5K9AyWkadxY/exec)

This is a starter project for web app which uses Clasp and Parcel to deploy modern Javascript to Google's Apps Script (GAS) projects V8 engine. 

Clone the repo, run `npm install`, install Clasp globally `npm install @google/clasp -g` and if prompted for a dependency, inquirer@^6.0.0,  run `npm install inquirer@^6.0.0 -g`.

Next install parcel `npm i parcel -g` and parcel-plugin-inliner `npm i parcel-plugin-inliner -g`.

Once it is setup, run your build with `npx parcel build client/index.html --no-minify --no-source-maps  --no-cache`.  I used the live server extension to test if the styling and javascript worked as expected. 

It includes the starter template for [Bootstrap 5](https://v5.getbootstrap.com/) with the sticky footer.  Instructions for importing it as a [Parcel Recipe](https://parceljs.org/recipes.html).

A .devcontainer for Node and Javascript Projects for [Github Codespaces](https://docs.github.com/en/github/developing-online-with-codespaces).

# References and Related Links
I used the walkthrough [CLASP Web App, Google Apps Script, Parcel JS, Nodemon, Node JS Workflow Setup Tutorial](https://www.youtube.com/watch?v=Nf9ExEkySjo), as a guide, as always this author does a great job in stepping through the example.

[Command Line Interface using clasp](https://developers.google.com/apps-script/guides/clasp)

[Clasp's GitHub TypeScript guide](https://github.com/google/clasp/blob/master/docs/typescript.md)

[Parcel's docs](https://v2.parceljs.org/)