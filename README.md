# initialize

<a href="https://github.com/kuriv/initialize">
	<img src="initialize.png" width="80" height="80" align="right">
</a>

> Build your meta-information in seconds.

[![build][build-image]][build-url]
[![version][version-image]][version-url]
[![license][license-image]][license-url]

## Installation

**npm**

```
npm install @kuriv/initialize
```

## What does it do?

* Collect and list HTML standard meta tags.
* Always use the latest version of the document mode.
* Build your web application more easily.

## Meta tags

### Declare the character encoding used by the document.

```html
<meta charset="utf-8"/>
```

### Enable DNS pre-resolving.

```html
<meta http-equiv="x-dns-prefetch-control" content="on"/>
```

### DNS pre-resolved domain name.

```html
<link rel="dns-prefetch" href="https://example.com"/>
```

### Give priority to the latest version of IE and Chrome.

```html
<meta http-equiv="X-UA-Compatible" content="IE=edge, chrome=1"/>
```

### Control the browser to render the page with the webkit kernel.

```html
<meta name="renderer" content="webkit"/>
```

### Add the authoritative link of the page.

```html
<link rel="canonical" href="https://example.com"/>
```

### Add the viewport to mobile device.

```html
<meta name="viewport" content="initial-scale=1.0, maximum-scale=1.0, user-scalable=0"/>
```

### Ignore phone numbers and email addresses on the page.

```html
<meta name="format-detection" content="telephone=no, email=no"/>
```

### Add the Windows 8 tile name.

```html
<meta name="application-name" content="Title"/>
```

### Add the Windows 8 tile color.

```html
<meta name="msapplication-TileColor" content="#000"/>
```

### Add the Windows 8 tile image.

```html
<meta name="msapplication-TileImage" content="/image.png"/>
```

### Display the download banner of the app on the page.

```html
<meta name="apple-itunes-app" content="app-id=, affiliate-data=, app-argument="/>
```

### Set the title added to the home screen.

```html
<meta name="apple-mobile-web-app-title" content="Title"/>
```

### Add the Standard iPhone icons, 57x57 pixels.

```html
<link rel="apple-touch-icon-precomposed" sizes="57x57" href="/image@57x57.png"/>
```

### Add the Standard iPad icons, 72x72 pixels.

```html
<link rel="apple-touch-icon-precomposed" sizes="72x72" href="/image@72x72.png"/>
```

### Add the Retina iPhone icons, 114x114 pixels.

```html
<link rel="apple-touch-icon-precomposed" sizes="114x114" href="/image@114x114.png"/>
```

### Add the Retina iPad icons, 144x144 pixels.

```html
<link rel="apple-touch-icon-precomposed" sizes="144x144" href="/image@144x144.png"/>
```

### Remove default toolbar and menu bar.

```html
<meta name="apple-mobile-web-app-capable" content="yes"/>
```

### Set the background color of the status bar.

```html
<meta name="apple-mobile-web-app-status-bar-style" content="default"/>
```

### Add the theme color to browser's toolbar. (Chrome for Android only)

```html
<meta name="theme-color" content="#fff"/>
```

### Put the search function on your browser's quick search tool.

```html
<link rel="search" type="application/opensearchdescription+xml" title="title" href="/opensearch.xml"/>
```

### Add the author of the page.

```html
<meta name="author" content="kuriv"/>
```

### Add the title of the page.

```html
<title>Title</title>
```

### Add the keywords of the page.

```html
<meta name="keywords" content="keywords, keywords, keywords"/>
```

### Add the description of the page.

```html
<meta name="description" content="description"/>
```

### Add the icon in front of the page title.

```html
<link rel="shortcut icon" type="image/x-icon" href="/farvirate.ico"/>
```

## License

`initialize` is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT) .



[build-image]: https://img.shields.io/badge/build-passing-brightgreen   "build"
[build-url]: https://github.com/kuriv/initialize	"build"
[version-image]: https://img.shields.io/badge/version-v1.0.1-blue   "version"
[version-url]: https://github.com/kuriv/initialize	"version"
[license-image]: https://img.shields.io/badge/license-MIT-green "license"
[license-url]: https://opensource.org/licenses/MIT	"license"