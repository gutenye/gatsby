# gatsby-plugin-sharp

Exposes several image processing functions built on the [Sharp image
processing library](https://github.com/lovell/sharp). This is a
low-level helper plugin generally used by other Gatsby plugins.  You
generally shouldn't be using this directly but might find it helpful if
doing very custom image processing.

It aims to provide excellent out-of-the box settings for processing
common web image formats.

For JPEGs it generates progressive images with a default quality level
of 50.

For PNGs it uses [pngquant](https://github.com/pornel/pngquant) to
compress images. By default it uses a quality setting of [50-75].

## Install

`npm install --save gatsby-plugin-sharp`

## How to use

```javascript
// In your gatsby-config.js
plugins: [
  `gatsby-plugin-sharp`,
]
```
