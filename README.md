# Web starter kit

This is a [gulp](http://gulpjs.com)-based package for jump starting web pages. It implements the following build tools:
- Local web server with livereload
- Sass compiler
- CSS autoprefixer
- CSS minifier
- Markdown compiler

Other features include:
- [normalize.css](https://github.com/necolas/normalize.css) & a slightly updated [box](https://github.com/mrmrs/box)-sizing rule.
- The [Merriweather](http://www.google.com/fonts/specimen/Merriweather) and [Merriweather Sans](http://www.google.com/fonts/specimen/Merriweather+Sans) web font stack.


## Using web starter kit

**Nodejs is required for running this web starter kit.**

1. `git clone git@github.com:brianzelip/web-starter-kit.git YourNewProject` - clones this repo to your local environment as `YourNewProject`
2. `cd YourNewProject`
3. `rm -rf .git` - force removes this repo's .git file to make way for your own
4. `git init` - initializes your own .git repo
5. `git add remote git@github.com/yourUserName/YourNewProject.git` - creates a new github repo from your new local repo
6. `npm install` - installs the gulp tools specified in package.json
7. `gulp` - opens `/dist/index.html` in your default browser at http://localhost:8000 and livereloads on any changes made to HTML, Sass, and Markdown files the `/src` directory

Design your new project in the `/src` directory. All edits made to the `/src` directory will build to the `/dist` directory upon file save.

The only real content included here besides the gulp build tools are `_generic.normalize.scss`, `_generic.box-sizing.scss`, and some HTML `<head>` metadata. Everything else is up to you.

You may need to edit the HTML language attribute as appropriate. And you'll probably want to remove some of the web font styles.

The CSS architecture is modeled after [Harry Roberts'](http://csswizardry.com) [ITCSS](http://itcss.io) approach. This approach suggests organizing CSS into global settings, tools, generic, base, objects, components, and trumps sections. This organizes CSS from generic to specific. For more background on ITCSS, see Harry's slide deck [Managing CSS Projects with ITCSS ](https://speakerdeck.com/dafed/managing-css-projects-with-itcss).