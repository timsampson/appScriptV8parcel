# Apps Script Template with Bootstrap 5 and Parcel [![clasp](https://img.shields.io/badge/built%20with-clasp-4285f4.svg)](https://github.com/google/clasp)

[Example Site URL](https://script.google.com/macros/s/AKfycbwZdZj7GoKXU2gEzTmdwt1DCLDouSG2FxNN_eu8b5K9AyWkadxY/exec)

This is a starter project for web app which uses Clasp and Parcel to deploy modern Javascript to Google's Apps Script (GAS) projects V8 engine. 

### Get Started

Clone the repo, run `npm install`, install Clasp globally `npm install @google/clasp -g` and if prompted for a dependency, inquirer@^6.0.0,  run `npm install inquirer@6.5.2 -g`.  If you use a codespace cloned from this repo, this is configured already, but you will still need to login once the codespace is created.

If you are using Codespaces, Log in to clasp `clasp login --no-localhost`, othewise you can use `clasp login` at the terminal. Clasp will be installed when the Codespace is initially setup.  

Delete the existing .clasp.json file and then create your starter web app: `clasp create --type webapp  --title "Your Title" --rootDir ./appsscript`

### Build and Deploy

To build your app and push it using clasp, use the command `npm run build`. Your dist files will be deleted automatically with each run. Files that are pushed to Google Apps Script hosting can be found int the appscript folder.  Each build overwrites them. 

Before you can view your webapp, you need an  initial deploy. One way is to run `clasp deploy --description "Initial Deploy"`, or you can change the description to anything you see fit.  You can also do this from the Apps Script dashboard, `clasp open` will get you to your project on the dashboard and from there you can use the menu options.

### Includes

Starter template for [Bootstrap 5](https://v5.getbootstrap.com/) with the sticky footer.  Instructions for importing it as a [Parcel Recipe](https://parceljs.org/recipes.html).

A .devcontainer for Node and Javascript Projects for [Github Codespaces](https://docs.github.com/en/github/developing-online-with-codespaces).

# References and Related Links
I followed the walkthrough *CLASP Web App, Google Apps Script, Parcel JS, Nodemon, Node JS Workflow Setup Tutorial* [Watch on Youtube](https://www.youtube.com/watch?v=Nf9ExEkySjo), as a guide, as always this author does a great job in stepping through the example.

[Command Line Interface using clasp](https://developers.google.com/apps-script/guides/clasp)

[Clasp's GitHub TypeScript guide](https://github.com/google/clasp/blob/master/docs/typescript.md)

