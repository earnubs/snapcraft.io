# Snapcraft.io

The codebase for http://snapcraft.io.

## Getting Started

To run this project, you need `npm`, `jekyll` and `sass` installed. E.g. Ubuntu:

``` bash
sudo apt install nodejs-legacy npm ruby-sass jekyll
```

Now, in the project folder, install nodejs dependencies:

``` bash
npm i
```

### Run the site

To fire up the project, run;

``` bash
node_modules/gulp/bin/gulp.js
```

This should open `http://localhost:3000/` in your browser.

## Deploy to Github Pages

To deploy to Github Pages under your local Github username, please run;

`gulp deploy`

You should then be able to view the site at: `http://YOUR-GITHUB-USERNAME.github.io/snapcraft.io`

## Licence

Code licensed [LGPLv3](http://opensource.org/licenses/lgpl-3.0.html) by [Canonical Ltd.](http://www.canonical.com/).

With ♥ from Canonical
