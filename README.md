# FontFace Swap

Achieves FOUT by loading the font under a different font family, then swapping the FontFace to the correct family. Relies on the natural waterfall of font-family definitions to fallback to the unstyled (system) font while the FontFace is loading.

## Inspiration

[A Comprehensive Guide To Font Loading Strategies](https://www.zachleat.com/web/comprehensive-webfonts) provides a great foundation to loading fonts on the modern web. However, the strategies for FOUT/FOFT propose using a class to do single/multi stage renders. This is extremely difficult to achieve in a maintainable way when you have a large CSS codebase that is largely generated (via Sass). This aims to be an alternate strategy that does not rely on brittle CSS rules.

## What is FOUT, FOFT, FOIT?
Check the [Webfont Glossary](https://www.zachleat.com/web/webfont-glossary/)

## To run

```
$ python -m SimpleHTTPServer 8000
```
