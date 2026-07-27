# SIT Canvas Design System — CSS Framework

[![npm](https://img.shields.io/npm/v/@sit-canvas/canvas-css.svg)](https://www.npmjs.com/package/@sit-canvas/canvas-css)

The SIT Canvas Design System CSS framework provides the Bootstrap-based visual foundation used by
Canvas React components. It is an independent package with no external registry dependency, so it
will not auto-update outside of releases published here.

***

## Installation

### CSS

```html
<head>
    ...
    <link
        rel="stylesheet"
        href="https://cdn.jsdelivr.net/npm/@sit-canvas/canvas-css/css/sit-canvas.css"
    />
    ...
</head>
```

### Vanilla JavaScript

Canvas CSS components make use of the [bootstrap v5.2 js library](https://getbootstrap.com/docs/5.2/getting-started/javascript/) as an external dependency. If you only need the visual parts, or if you are using a frontend framework like React, you do not need to import this.

> `@sit-canvas/canvas-css` uses `bootstrap-icons` for certain components like Form but does not ship with it. Install `bootstrap-icons` or use a CDN if you need it. Please refer to [bootstrap-icons](bootstrap-icons) for usage instructions.

```html
<head>
  ...
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@sit-canvas/canvas-css/css/sit-canvas.css" />
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css">
  ...
</head>

<body>
  ...
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
    crossorigin="anonymous"></script>
</body>
```

### Via NPM

```sh
$ npm i @sit-canvas/canvas-css bootstrap-icons
```

### For Webpack

```js
//importing css
import '@sit-canvas/canvas-css/css/sit-canvas.css';

import '@popperjs/core';
import * as bootstrap from 'bootstrap';
```

***

## Patch Notes

See [Changelog](./CHANGELOG.md)
