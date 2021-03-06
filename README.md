![Slush Tangerine Logo](https://github.com/afonsopacifer/slush-tangerine/blob/master/logo.png)

# Slush Tangerine

> Front-End boilerplate generator with tangerine flavor.

## How to install and use the generator?

Install the slush:

```sh
$ [sudo] npm install -g slush
```

Install the tangerine generator:

```sh
$ [sudo] npm install -g slush-tangerine
```

Use the generator:

```sh
$ slush tangerine
```

## The generated boilerplate

Basic docs:

- [Getting Started](https://github.com/afonsopacifer/slush-tangerine/blob/master/DOCS.md)

Stack based in NodeJS:

- Generator: [Slush](http://slushjs.github.io/#/)
- Task Runner: [Gulp](http://gulpjs.com/)
- HTML Template Engine: [Jade](http://jade-lang.com/)
- CSS Post Processor: [PostCSS](https://github.com/postcss/postcss)
- JS Traspiler: [BabelJS](https://babeljs.io/)
- Test Runner: [Karma](https://www.npmjs.com/package/karma)
- Test Framework: [Jasmine](https://github.com/karma-runner/karma-jasmine)
- "Browser" for test: [PhantomJS](http://phantomjs.org/)

Vendors:

- CSS Reset: [Normalize](https://necolas.github.io/normalize.css/)

Folders Structure:

	.
	├── README.md
	├── out/
	├── tests/
	├── src/
	|   ├── assets/
	|   ├── includes/
	|   ├── partials/
	|   ├── layouts/
	|   └── index.jade
	├── config.json
	├── gulpfile.js
	├── package.json
	├── karma.conf.js
	├── .editorconfig
	├── .jshintrc
	└── .gitignore

Automatic Tasks:

- `$ gulp build`: Compile, concat and minify all files.
- `$ gulp serve`: Watch the files to build and start a static server.
- `$ gulp deploy`: Deploy for gh-pages.
- `$ gulp validate`: Code quality (JS Hint).
- `$ karma start`: Launch a Phantomjs and watch for unit tests.

## Versioning

To keep better organization of releases we follow the [Semantic Versioning 2.0.0](http://semver.org/) guidelines.

## Contributing

Find on our [roadmap](https://github.com/afonsopacifer/slush-tangerine/issues/1) the next steps of the project ;)
<br>
Want to contribute? [Follow these recommendations](https://github.com/afonsopacifer/slush-tangerine/blob/master/CONTRIBUTING.md).

## History

See [Releases](https://github.com/afonsopacifer/slush-tangerine/releases) for detailed changelog.

## License

[MIT License](https://github.com/afonsopacifer/slush-tangerine/blob/master/LICENSE.md) © [Afonso Pacifer](http://afonsopacifer.com/)
