# reset.css

An [unmodified\*](#changelog) copy of Eric Meyer's [CSS reset](https://meyerweb.com/eric/tools/css/reset/).

## Install

With curl:

```command
$ curl -O "https://unpkg.com/reset-css@4.0.1/reset.css"
$ curl -O "https://unpkg.com/reset-css@4.0.1/sass/_reset.scss"
$ curl -O "https://unpkg.com/reset-css@4.0.1/less/reset.less"
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
<link rel="stylesheet" href="/path/to/reset-css/reset.css" />
```

CSS:

```css
@import '/path/to/reset-css/reset.css';
```

Via PostCSS and [postcss-import](https://github.com/postcss/postcss-import):

```css
@import 'reset-css';
```

Via webpack and [css-loader](https://github.com/webpack-contrib/css-loader):

```js
import 'reset-css';
```

Via Sass:

```scss
@import '/path/to/reset-css/sass/reset';
```

Via Less:

```less
@import '/path/to/reset-css/less/reset';
```

## \*Changelog

Two changes have been made from the 2011 version, both approved by [Mr. Meyer](https://github.com/meyerweb):

- Added `main` to list of HTML 5 elements [(#7)](https://github.com/shannonmoeller/reset-css/pull/7#issuecomment-233969617)
- Added rule to fix `hidden` attribute on HTML 5 elements [(#12)](https://github.com/shannonmoeller/reset-css/issues/12#issuecomment-372821712)

----

Eric Meyer http://meyerweb.com/eric/tools/css/reset/

License: none (public domain)
