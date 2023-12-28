# Parcel Sass Builder

A relatively simple utility to compile SASS files into basic CSS. Intended for content authors working in AEM that can't modify components but need to build CSS from outside the AEM system.

## Setup

Setup is as simple as:

`npm install` or `yard install` depending on your inclinations.

This utility has three functions you can run.

1. `npm run build` - Prettifies and compiles SASS files into CSS without any other functions
2. `npm run watch` - On change, will Prettify and compile any files that have been updated
3. `npm run serve` - Starts a small server on port 8888 to serve the CSS files that have been compiled. It will continue to watch for changes and rebuild the files as necessary.

Hot Module Reloading is not enabled here. Please see the Parcel [docs](https://parceljs.org/features/cli/#parameters-specific-to-serve-and-watch) for more information on how to do that.
