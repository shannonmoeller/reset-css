# `reset.css`

An [unmodified\*](#changelog) copy of Eric Meyer's [CSS reset](https://meyerweb.com/eric/tools/css/reset/).

## Install

With curl:

```command
$ curl -O "https://unpkg.com/reset-css@3.0.0/reset.css"
```

With [NPM](http://npmjs.com):

```command
$ npm install --save reset-css
```

With [Yarn](https://yarnpkg.com):

```command
$ yarn add reset-css
```

With [Bower](http://bower.io):

```command
$ bower install reset-css
```

## Usage

HTML:

```html
<link rel="stylesheet" href="/assets/reset-css/reset.css" />
```

CSS:

```css
@import '/assets/reset-css/reset.css';
```

PostCSS and [postcss-import](https://github.com/postcss/postcss-import):

```css
@import 'reset-css';
```

Webpack and [css-loader](https://github.com/webpack-contrib/css-loader):

```js
import reset from 'reset-css';
```

Sass:

```scss
@import '/assets/reset-css/_reset';
```

Less:

```less
@import '/assets/reset-css/reset';

// or

@import (inline) '/assets/reset-css/reset.css';
```

## \*Changelog

Two changes have been made from the 2011 version, both approved by [Mr. Meyer](https://github.com/meyerweb):

- Added `main` to list of HTML 5 elements [(#7)](https://github.com/shannonmoeller/reset-css/pull/7#issuecomment-233969617)
- Added rule to fix `hidden` attribute on HTML 5 elements [(#12)](https://github.com/shannonmoeller/reset-css/issues/12#issuecomment-372821712)

----

Eric Meyer http://meyerweb.com/eric/tools/css/reset/

License: none (public domain)
