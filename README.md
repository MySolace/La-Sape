# lasape

La Sape is Crisis Text Line's live pattern library/style guide. It is built on top of [Fabricator](https://github.com/fbrctr/fabricator) is a highly-modular design system for rapid web page development. It contains different materials that can be assembled into more complex page layouts.

## Getting Started

Fabricator requires [node.js](http://nodejs.org), so make sure your have `v0.10` or higher installed before proceeding.

**Start the local development environment:**

```
$ npm start
```

## Compiling to static HTML

1. When you are done making your changes, make sure to run the following, to compile the production version of the static HTML and asset files:

```
$ npm run build
```

2. Once the build script has finished, commit the changes to the `gh-pages` branch and push up.

3. You can then commit the changes in the base up in its own commit.

Fabricator builds both a static documentation site and optimized CSS and JS toolkit files. Static files are compiled in the `dist` directory. You can view the files here: [http://crisistextline.github.io/La-Sape](http://crisistextline.github.io/La-Sape)
