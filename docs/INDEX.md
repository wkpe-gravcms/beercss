## Get started

#### CDN

From jsdelivr.net.

```html
<link href="https://cdn.jsdelivr.net/npm/beercss@2.2.11/dist/cdn/beer.min.css" rel="stylesheet" />
<script src="https://cdn.jsdelivr.net/npm/beercss@2.2.11/dist/cdn/beer.min.js" type="text/javascript"></script>
<script src="https://cdn.jsdelivr.net/npm/material-dynamic-colors@0.0.10/dist/cdn/material-dynamic-colors.min.js" type="text/javascript"></script>
```

#### NPM

You can get the latest release using NPM. This release contains source files as well as the compiled CSS and JavaScript files.

```js
// installing
npm i material-dynamic-colors
npm i beercss
```

```js
// importing
import "material-dynamic-colors";
import "beercss";
```

### HTML

You can use this html to setup your project. See on [Codepen](https://codepen.io/leo-bnu/pen/yLKLPxj).

```html
<html>
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <meta name="google" content="notranslate">
    <title>Hello world</title>
    <link href="https://cdn.jsdelivr.net/npm/beercss@2.2.11/dist/cdn/beer.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/beercss@2.2.11/dist/cdn/beer.min.js" type="text/javascript"></script>
    <script src="https://cdn.jsdelivr.net/npm/material-dynamic-colors@0.0.10/dist/cdn/material-dynamic-colors.min.js" type="text/javascript"></script>
  </head>
  <body class="light">
    <nav class="left m l">
      <img src="https://www.beercss.com/favicon.png" class="circle margin">
      <a>
        <i>home</i>
        <div>Home</div>
      </a>
      <a>
        <i>search</i>
        <div>Search</div>
      </a>
      <a>
        <i>share</i>
        <div>Share</div>
      </a>
      <a>
        <i>more_vert</i>
        <div>More</div>
      </a>
    </nav>
    
    <nav class="bottom s">
      <a>
        <i>home</i>
      </a>
      <a>
        <i>search</i>
      </a>
      <a>
        <i>share</i>
      </a>
      <a>
        <i>more_vert</i>
      </a>
    </nav>
    
    <main class="responsive">
      <img src="https://www.beercss.com/beer-and-woman.jpg" class="responsive round">
      <h3>Welcome</h3>
      <h5>The beer is ready!</h5>
    </main>
  </body>
</html>
```

**We recommend use the material-dynamic-colors only when your app needs to change theme at runtime.**

## [Settings](SETTINGS.md)

The settings affects all document.

## [Elements](ELEMENTS.md)

The elements are the components, widgets or tags.

## [Helpers](HELPERS.md)

The common helpers makes the elements more scalable and customizable.

## Tips to master beercss

1. Try use helpers first, before any custom css.
2. To customize themes go to [Settings](SETTINGS.md).
3. To quick learn the project go to [Summary](SUMMARY.md).

## Go to

[Begin](INDEX.md), [Elements](ELEMENTS.md), [Helpers](HELPERS.md), [Settings](SETTINGS.md), [Summary](SUMMARY.md), [beercss.com](https://www.beercss.com)

[Badge](BADGE.md), [Button](BUTTON.md), [Card](CARD.md), [Checkbox](CHECKBOX.md), [Chip](CHIP.md), [Container](CONTAINER.md), [Dropdown](DROPDOWN.md), [Expansion](EXPANSION.md), [Grid](GRID.md), [Icon](ICON.md), [Input](INPUT.md), [Layout](LAYOUT.md), [Loader](LOADER.md), [Media](MEDIA.md), [Modal](MODAL.md), [Navigation](NAVIGATION.md), [Overlay](OVERLAY.md), [Page](PAGE.md), [Progress](PROGRESS.md), [Radio](RADIO.md), [Select](SELECT.md), [Switch](SWITCH.md), [Table](TABLE.md), [Tabs](TABS.md), [Textarea](TEXTAREA.md), [Toast](TOAST.md), [Tooltip](TOOLTIP.md), [Typography](TYPOGRAPHY.md)
