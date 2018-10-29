# Sass (Syntactically Awesome StyleSheets)

## What is it?

- Defines a language that "makes CSS fun again"
- It's CSS with extended capabilities
- Compiles to regular CSS for production use
- Has implementations in many languages
  - At first in Ruby
  - Then rewritten in Dart
  - Unofficial implementations in C/C++, Go, and other languages exist
- You don't need to know how it's implemented to use it
- Two syntaxes exist
  - SCSS (newer, files end in `.scss`)
  - Sass (older, files end in `.sass`) — uses indentation instead of curly
    braces, like YAML
- Benefit of the first syntax is that regular CSS is valid

To get started, `npm install -g sass`

This tool converts Sass files into CSS files.

`sass example.scss out.css` or `sass --watch example.scss out.css`

Type `sass --help` for more options.

## Why is it useful?

- Makes CSS easier to write
- Variables
- Nested selectors help avoid repetition of selectors and organize code
- Break up large CSS files into multiple smaller files and combine then in a
  build process (known as partials)
- Mixins allow reuse of a group of CSS declarations
- Do math
- Integrates well with Gulp, Webpack, etc.

## References

- http://sass-lang.com/
- http://sass-lang.com/documentation/file.SASS_REFERENCE.html
- https://github.com/sass/sass
