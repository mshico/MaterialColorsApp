# Material Colors for Linux

A handy little Linux app that gives you quick access to the standard material design color palette.

<img src="https://d13yacurqjgara.cloudfront.net/users/6295/screenshots/2594885/colors_2x.png" width="300" alt="Screenshot">
 
## Build instructions

If you want to customize the app for your own needs, you can do a custom build.

  1. First install [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/).
  2. Clone the repository and in the root directory, run:

        $ npm install

  3. To run the app
        
        $ npm start

  4. To run the app using gulp (you can install gulp using `npm install --global gulp-cli`):

        $ gulp

Note that you'll probably want to disable the auto-updating mechanism by emptying out the `checkForUpdates` method in
[main.js](https://github.com/romannurik/MaterialColorsApp/blob/master/app/main.js).
