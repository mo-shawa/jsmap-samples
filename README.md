![Build](https://github.com/googlemaps/js-samples/workflows/Build/badge.svg)
![Release](https://github.com/googlemaps/js-samples/workflows/Release/badge.svg)
![GitHub contributors](https://img.shields.io/github/contributors/googlemaps/js-samples)
![Apache-2.0](https://img.shields.io/badge/license-Apache-blue)

js-samples
==========

## Description
Samples for the Google Maps JavaScript API.

**[View the samples](https://storage.googleapis.com/js-samples/master/public/index.html)**

**Note::** Many of these samples were written in 2010-2012. Many are still functional and are in the samples folder. Others that do not run have been moved to archive.

## Development
1. Set the environment variable `export GOOGLE_MAPS_JS_SAMPLES_KEY=YOUR_KEY`.
1. Install with `yarn install`.
1. Start a server with all samples using `yarn run serve`.

Bazel is used for the build system and can be called with `yarn run bazel`.

## Other Resources
- [Google Maps Documentation](https://developers.google.com/maps/documentation/javascript/tutorial)
- [Google Maps Reference Documenations](https://developers.google.com/maps/documentation/javascript/reference/)
- [Google Maps Typings](https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/googlemaps) - Community supported `yarn i -D @types/googlemaps`
- [Google Maps Utilitiies](https://github.com/googlemaps/v3-utility-library)

## Support

These libraries are community supported. We're comfortable enough with the stability and features of
the libraries that we want you to build real production applications on it.

If you find a bug, or have a feature suggestion, please [log an issue][issues]. If you'd like to
contribute, please read [How to Contribute][contrib].
