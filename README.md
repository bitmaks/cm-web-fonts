# Computer Modern Web Fonts
The Computer Modern Font Family (the default LaTeX font), delivered on the web.

## Usage
Link this stylesheet: `https://cdn.jsdelivr.net/gh/aaaakshat/cm-web-fonts@latest/fonts.css` in your html `<head>`.

### HTML Code
```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/aaaakshat/cm-web-fonts@latest/fonts.css">
```

### Web demo
Check out [https://checkmyworking.com/cm-web-fonts/]() to get download links and see a customisable demo of the Computer Modern font family. Or visit [TeXBlog](https://texblog.akshatbisht.com) to view a working implementation of a site fetching from this CDN.

### Example Code
```html
<head>
  <!-- Other imports... -->
  <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/aaaakshat/cm-web-fonts@latest/fonts.css">
  <style>
    body {
      font-family: "Computer Modern Serif", serif;
    }
  </style>
</head>
```
### License 
The font is licensed under the [SIL Open Font License](./LICENSE.txt). The license gives you permission to use them online and redistribute/modify/study them so long as you keep the resulting fonts under the Open Font License. _I'm not a lawyer and I can't give legal advice, so make sure to read the [official OFL FAQs](./LICENSE-FAQ.txt)._

## Fonts
The folowing font families are included (with bold and italics):
* `'Computer Modern Bright'`
* `'Computer Modern Concrete'`
* `'Computer Modern Sans'`
* `'Computer Modern Serif'`
* `'Computer Modern Typewriter'`

## Delivery
Files are served via jsDelivr, an free, open-source CDN supported by companies like CloudFlare. jsDelivr serves ~72 billion requests/month and is has been reliable for me; however, there's no such thing as a free lunch and I cannot guarantee 100% uptime.  Use it at your own risk.

## Credits
Repo forked from [@dreampulse](http://www.github.com/dreampulse),  cm-unicode web fonts compiled by [Christian Perfect](http://checkmyworking.com) from the [Computer Modern Unicode fonts](http://cm-unicode.sourceforge.net/) created by Andrey V. Panov. The original Computer Modern fonts were created by Donald Knuth et al. 

