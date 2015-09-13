# cookiecutter-babel

A minimal [Babel](https://babeljs.io/) based ES6
[Cookiecutter](https://github.com/audreyr/cookiecutter) template.

## Usage

Get cookiecutter as per cookiecutter instructions, and then create a project:

```
$ cookiecutter gh:Raynes/cookiecutter-babel
$ cd aegaeon # replace with your actual project name
$ npm install
$ gulp # builds ES6 source code in src/
```

There's also a little task in there to watch `src/` and autocompile in the
background:

```
$ gulp watch
```

You can run the little program like so:

```
$ node lib/aegaeon.js
```

Make sure you compile `src/` after each change or keep `gulp watch` running!

## Resources

[ES6](https://babeljs.io/docs/learn-es2015/)
[Babel](https://babeljs.io/)
[ESLint](http://eslint.org/)
