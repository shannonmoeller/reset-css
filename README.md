# reset.css

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

## Usage in Plain HTML and CSS

Copy `reset.css` to a directory, ideally where your CSS is.

HTML:

```html
<link rel="stylesheet" href="/your/directory/reset.css" />
```

CSS:

```css
@import '/your/directory/reset.css';
```

## Usage in Build Tools and Preprocessors

PostCSS and [postcss-import](https://github.com/postcss/postcss-import):

```css
@import 'reset-css';
```

webpack and [css-loader](https://github.com/webpack-contrib/css-loader):

```js
import reset from 'reset-css';
```

Sass:

```scss
@import "./../path/to/node_modules/reset-css/reset.scss";

// or if using webpack

@import "~reset-css/reset.scss";

// or if you copied the reset.scss file to your project

@import '/your/directory/_reset';
```

Less:

```less
@import "./../path/to/node_modules/reset-css/reset.scss";

// or if using webpack

@import "~reset-css/reset.scss";

// or if you copied the reset.scss file to your project

@import '/your/directory/_reset.scss';

// or you can do any of the above using the reset.css file with (inline):

@import (inline) '/your/directory/reset.css';
```

## \*Changelog

Two changes have been made from the 2011 version, both approved by [Mr. Meyer](https://github.com/meyerweb):

- Added `main` to list of HTML 5 elements [(#7)](https://github.com/shannonmoeller/reset-css/pull/7#issuecomment-233969617)
- Added rule to fix `hidden` attribute on HTML 5 elements [(#12)](https://github.com/shannonmoeller/reset-css/issues/12#issuecomment-372821712)

----

Eric Meyer http://meyerweb.com/eric/tools/css/reset/

License: none (public domain)
