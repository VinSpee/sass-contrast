# sass-contrast

A simple Sass contrast mixin written by [Brendan Saunders](http://twitter.com/bluesaunders).

## API
```
$dark-text-default: #000 !default;
$light-text-default: #fff !default;

html {
	background: $your-color;
	@include contrasted($your-color[, $return-this-dark-color, $return-this-light-color]);
}
```

## Installation

`bower install --save-dev sass-contrast`
