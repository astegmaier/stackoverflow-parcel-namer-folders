# An example of how to write a custom parcel namer.

This repo contains two packages:

1. `parcel-namer-folders` - a simple Parcel Namer plugin that puts css and javascript bundles into separate folders
2. `app` - a sample app that is configured to build with parcel, using this plugin.

It was written to demonstrate the solution to [a stackoverflow question](https://stackoverflow.com/questions/62900160/how-to-handle-output-files-in-parcel)

### Setup instructions

1. Run `yarn install`
2. Run `yarn app build`
3. See that the output javascript files in `app/dist` have the `min.js` extension.
