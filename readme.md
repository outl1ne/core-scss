# Optimist Digital | Core SCSS

This is a SCSS partial that provides some utility mixins and default styles that fit our workflow.

Some of the partials utilize variables that you may define in your project before including these partials. If not defined, we define defaults in `partials/_default-config.scss`.

## Usage

Add `@import "node_modules/@optimistdigital/core-scss/core";` before your component mixins, after your variable definitions.

## Features

The exact purpose of each mixin is explained in `_core.scss`. Other than the default styles, Here are the mixins that we provide:

- `@mixin clearfix()`
- `@mixin ellipsis()`
- `@mixin body-font()`
- `@mixin heading-font()`
- `@mixin maxwidth-wrapper()`
- `@mixin reset-list()`
- `@mixin bp($width)`
- `@mixin minbp($width)`
