# Primer CSS / Popover

[![npm version](http://img.shields.io/npm/v/primer-popover.svg)](https://www.npmjs.org/package/primer-popover)
[![Build Status](https://travis-ci.org/primer/primer-css.svg?branch=master)](https://travis-ci.org/primer/primer-css)

> Popover for suggesting, guiding, and bringing attention to specific UI elements on a page.

This repository is a module of the full [primer-css][primer-css] repository.

## Install

This repository is distributed with [npm]. After [installing npm][install-npm], you can install `primer-popover` with this command.

```
$ npm install --save primer-popover
```

## Usage

The source files included are written in [Sass][sass] (SCSS) You can simply point your sass `include-path` at your `node_modules` directory and import it like this.

```scss
@import "primer-popover/index.scss";
```

You can also import specific portions of the module by importing those partials from the `/lib/` folder. _Make sure you import any requirements along with the modules._

## Build

For a compiled **CSS** version of this module, an npm script is included that will output a css version to `build/build.css` The built css file is also included in the npm package:

```
$ npm run build
```

## Documentation

<!-- %docs
title: Popover
status: Experimental
-->

### Basic example
Defaults to caret oriented top-center.

```html title="Default (top-center)"
<div class="position-relative text-center">
  <button class="btn btn-primary">UI</button>
  <div class="Popover right-0 left-0">
    <div class="Popover-message text-left p-4 mt-2 mx-auto Box box-shadow-large">
      <h4 class="mb-2">Popover heading</h4>
      <p>Message about this particular piece of UI.</p>
      <button type="submit" class="btn btn-outline mt-2 text-bold">Got it!</button>
    </div>
  </div>
</div>
```

### Large example

```html title="Large"
<div class="position-relative text-center">
  <button class="btn btn-primary">UI</button>
  <div class="Popover right-0 left-0">
    <div class="Popover-message Popover-message--lg text-left p-4 mt-2 Box box-shadow-large">
      <h4 class="mb-2">Popover heading</h4>
      <p>Message about this particular piece of UI.</p>
      <button type="submit" class="btn btn-outline mt-2 text-bold">Got it!</button>
    </div>
  </div>
</div>
```

### Top-right-aligned example

```html title="Top-right"
<div class="position-relative text-right">
  <button class="btn btn-primary">UI</button>
  <div class="Popover right-0">
    <div class="Popover-message Popover-message--top--right text-left p-4 mt-2 Box box-shadow-large">
      <h4 class="mb-2">Popover heading</h4>
      <p>Message about this particular piece of UI.</p>
      <button type="submit" class="btn btn-outline mt-2 text-bold">Got it!</button>
    </div>
  </div>
</div>
```

### Top-right-aligned example

```html title="Top-left"
<div class="position-relative">
  <button class="btn btn-primary">UI</button>
  <div class="Popover">
    <div class="Popover-message Popover-message--top--left p-4 mt-2 Box box-shadow-large">
      <h4 class="mb-2">Popover heading</h4>
      <p>Message about this particular piece of UI.</p>
      <button type="submit" class="btn btn-outline mt-2 text-bold">Got it!</button>
    </div>
  </div>
</div>
```

### Right-aligned example

```html title="Right"
<div class="Popover">
  <div class="Popover-message Popover-message--right p-4 mt-2 Box box-shadow-large">
    <h4 class="mb-2">Popover heading</h4>
    <p>Message about this particular piece of UI.</p>
    <button type="submit" class="btn btn-outline mt-2 text-bold">Got it!</button>
  </div>
</div>
```

### Left-aligned example

```html title="Left"
<div class="Popover">
  <div class="Popover-message Popover-message--left p-4 mt-2 Box box-shadow-large">
    <h4 class="mb-2">Popover heading</h4>
    <p>Message about this particular piece of UI.</p>
    <button type="submit" class="btn btn-outline mt-2 text-bold">Got it!</button>
  </div>
</div>
```

### Bottom-aligned example

```html title="Bottom"
<div class="Popover">
  <div class="Popover-message Popover-message--bottom p-4 mt-2 mx-auto Box box-shadow-large">
    <h4 class="mb-2">Popover heading</h4>
    <p>Message about this particular piece of UI.</p>
    <button type="submit" class="btn btn-outline mt-2 text-bold">Got it!</button>
  </div>
</div>
```

### Bottom-right-aligned example

```html title="Bottom-right"
<div class="Popover">
  <div class="Popover-message Popover-message--bottom--right p-4 mt-2 mx-auto Box box-shadow-large">
    <h4 class="mb-2">Popover heading</h4>
    <p>Message about this particular piece of UI.</p>
    <button type="submit" class="btn btn-outline mt-2 text-bold">Got it!</button>
  </div>
</div>
```

### Bottom-left-aligned example

```html title="Bottom-left"
<div class="Popover">
  <div class="Popover-message Popover-message--bottom--left p-4 mt-2 mx-auto Box box-shadow-large">
    <h4 class="mb-2">Popover heading</h4>
    <p>Message about this particular piece of UI.</p>
    <button type="submit" class="btn btn-outline mt-2 text-bold">Got it!</button>
  </div>
</div>
```

<!-- %enddocs -->

## License

[MIT](./LICENSE) &copy; [GitHub](https://github.com/)

[primer-css]: https://github.com/primer/primer
[docs]: http://primercss.io/
[npm]: https://www.npmjs.com/
[install-npm]: https://docs.npmjs.com/getting-started/installing-node
[sass]: http://sass-lang.com/