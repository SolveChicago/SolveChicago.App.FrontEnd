# ZURB Template for Solve Chicago


This is the ZURB Template from [Foundation for Sites](http://foundation.zurb.com/sites). It has a Gulp-powered build system with these features:

- Handlebars HTML templates with Panini
- Sass compilation and prefixing
- JavaScript concatenation
- Built-in BrowserSync server
- For production builds:
  - CSS compression
  - JavaScript compression
  - Image compression

## Installation

To use this system, your computer needs:

- [NodeJS](https://nodejs.org/en/) (0.12 or greater)
- [Git](https://git-scm.com/)


### Install the CLI

Install the Foundation CLI with this command:

```bash
npm install foundation-cli --global
```

Then open the folder in your command line, and install the needed dependencies:

```bash
cd to-directory-path
npm install
bower install
```

Now `cd` to your project name and to start your project run 

```bash
foundation watch
```


Finally, run `npm start` to run Gulp. Your finished assets will be created in a folder called `dist`, viewable at this URL:

```
http://localhost:8000
```

To see Styleguide
```
http://localhost:8000/styleguide.html
```

To see all other pages, name it at the end of the URL
```
http://localhost:8000/template-name.html
```


To create compressed, production-ready assets, run `npm run build`.
