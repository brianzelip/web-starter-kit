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

1. `git clone git@github.com:brianzelip/web-starter-kit.git YourNewProject` (clone this repo to your local environment as `YourNewProject`)
2. `cd YourNewProject`
3. `rm -rf .git` (force removes this repo's `.git` file to make way for your own)
4. `git init` (initialize your own `.git` repo)
5. `git add remote git@github.com/yourUserName/YourNewProject.git` (create a new github repo from your new local repo)

Make your new project in the `src` directory. All edits made to the `src` directory will build to the `dist` directory.


## Influences

- Harry Roberts' [ITCSS](http://itcss.io) for css architecture