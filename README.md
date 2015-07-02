# Prepare.css

> Preparing our CSS for a object-oriented environment

Based on [SUIT CSS base](https://github.com/suitcss/base).

Dependent on something adding vendor prefixes, such as [Autoprefixer](https://github.com/postcss/autoprefixer)

## Install

```sh
$ npm install prepare.css
```

Example usage:
```css
/* Base */
@import "normalize.css"; 
@import "prepare.css";

/* Components */
@import "components/site.css"; /* Setting base font, background, and site layout styles */
@import "components/type.css"; /* For typography elements and user generated content */
@import "components/button.css";

/* Utilities */
@import "utilities/link.css"; /* Maybe an `.u-link` class for displaying styled links */
```
