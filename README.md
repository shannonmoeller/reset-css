# `reset.css`

An unmodified copy of Eric Meyer's CSS reset.

## Install

With [Bower](http://bower.io):

    $ bower install reset-css

With [NPM](http://npmjs.com):

    $ npm install --save reset-css

## Usage

### Bower

HTML:

```html
<link rel="stylesheet" href="bower_components/reset-css/reset.css" />
```

CSS:

```css
@import 'bower_components/reset-css/reset.css';
```

Sass:

```scss
@import 'bower_components/reset-css/_reset';
```

Less:

```less
@import 'bower_components/reset-css/reset';

// or

@import (inline) 'bower_components/reset-css/reset.css';
```

### NPM

PostCSS and [postcss-import](https://github.com/postcss/postcss-import):

```css
@import 'reset-css/reset.css';
```

----

Eric Meyer http://meyerweb.com/eric/tools/css/reset/

License: none (public domain)
