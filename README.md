# initialize

<a href="https://github.com/kuriv/initialize">
	<img src="https://raw.githubusercontent.com/kuriv/kuriv.github.io/master/.cloud/initialize/30db597822c6e06c6737052260426f45.svg?sanitize=true" width="68" height="68" align="right">
</a>

> Build your meta-information in seconds.

[![build][build-image]][build-url]
[![version][version-image]][version-url]
[![license][license-image]][license-url]

**Download**

See [https://kuriv.github.io/initialize/initialize.html](https://kuriv.github.io/initialize/initialize.html)

## What does it do?

* Collect and list HTML common meta tags.
* Define the rendering kernel of common browsers.
* Explains what meta tags does using detailed comments.
* Build your web application more easily.

## How to use it?

It's suggested that you read the `initialize.html` file and consider customising it to meet your needs.

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

### Enable 360 browser extreme speed mode (webkit).

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

### Windows 8 tile name.

```html
<meta name="application-name" content="Title"/>
```

### Windows 8 tile color.

```html
<meta name="msapplication-TileColor" content="#000"/>
```

### Windows 8 tile image.

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

### Standard iPhone icons, 57x57 pixels.

```html
<link rel="apple-touch-icon-precomposed" sizes="57x57" href="/image@57x57.png"/>
```

### Standard iPad icons, 72x72 pixels.

```html
<link rel="apple-touch-icon-precomposed" sizes="72x72" href="/image@72x72.png"/>
```

### Retina iPhone icons, 114x114 pixels.

```html
<link rel="apple-touch-icon-precomposed" sizes="114x114" href="/image@114x114.png"/>
```

### Retina iPad icons, 144x144 pixels.

```html
<link rel="apple-touch-icon-precomposed" sizes="144x144" href="/image@144x144.png"/>
```

### Remove iPhone's default toolbar and menu bar.

```html
<meta name="apple-mobile-web-app-capable" content="yes"/>
```

### Set the background color of the status bar.

```html
<meta name="apple-mobile-web-app-status-bar-style" content="default"/>
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

`initialize` is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).



[build-image]: https://raw.githubusercontent.com/kuriv/kuriv.github.io/master/.cloud/initialize/00dcfa5a92fb9b4242304a520c1ba9eb.svg?sanitize=true
[build-url]: https://github.com/kuriv/initialize
[version-image]: https://raw.githubusercontent.com/kuriv/kuriv.github.io/master/.cloud/initialize/73dad62fc2aa7c39fe32343a9ec18b54.svg?sanitize=true
[version-url]: https://github.com/kuriv/initialize
[license-image]: https://raw.githubusercontent.com/kuriv/kuriv.github.io/master/.cloud/initialize/1ddce524c69082e65c8e1f71c4f02a23.svg?sanitize=true
[license-url]: https://opensource.org/licenses/MIT