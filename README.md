# React-Typescript-Express-Webpack-Starter

A boilderplate for using React with Typescript, using Express to serve and webpack to transpile and bundle.

## Getting started

First run `npm install`

-   To build the files, run `npm run build` which will run webpack and output the bundle files to `dist` directory. You can then open `index.html` from `dist` to view the app.
-   To run the server in a dev environment, run `npm run start` to have webpack recompile as your source files change, and express to host the server on `http://localhost:3000/`

## Dev Tooling

The following is a list of optional dev tooling that I included to help my workflow:

-   TSLint: A linter for Typescript. My linting settings are checked into the repo under `tslint.json`. (Can either be run with `npm run lint` or use the VSCode extention for in editior linting)
-   Prettier: A formatter to autostyle my code. You need the `prettier` VSCode extention. Prettier uses `.prettierrc.json` to set autoformatting style. Make sure your prettier seetings match your tslint settings, for example, `tslint.json` is set up to never allow semicolons unless necessary, so my `.prettierrc.json` auto removes semicolons unless necessary.
