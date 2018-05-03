# grunt-node-sass

## Getting Started

```shell
npm install grunt-node-sass --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-node-sass');
```

## Example:

```js
sass: {
    dist: {
        src: 'source.scss',
        dest: 'build.css',

        options: {
            sourceComments: true,
            outputStyle: "nested"
        }
    }
},
```

## Options

Some simple Sass options

### sourceComments

- Type: `Boolean`
- Default: `false`

### outputStyle

- Type: `String`
- Default: `nested`
- Values: `nested`, `expanded`, `compact`, `compressed`
