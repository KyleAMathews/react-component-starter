react-component-starter
=======================

Quickstart for creating a Coffeescript React component with a demo page.

Clone and copy and you're most of the way to releasing that sweet new
react.js component you wrote.

## Instructions

### Development
`make watch` runs webpack's dev server. Open http://localhost:8080 and
your examples will live reload via
https://github.com/gaearon/react-hot-loader

### Releases
Make a new release by running either `make release-patch` or `make
release-minor` or `make-release-major` and then run `make publish`

This will tag the release and increment package.json, then compile your
 code to `dist/`, and then publish the new release to NPM.

### Publish examples to github.
Ensure there's a `gh-pages` branch first then run `make
publish-gh-pages`
