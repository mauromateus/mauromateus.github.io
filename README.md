# mauromateus.github.io

Origin root for the GitHub Pages user site.

It exists so Android apps built as a Trusted Web Activity (TWA) for the demo projects hosted under this origin can be verified. Digital Asset Links requires the file at the root of the origin:

`/.well-known/assetlinks.json`

`.nojekyll` is required, otherwise Pages ignores the `.well-known` folder.

## Current state

`assetlinks.json` is an empty list. It is filled with the package name and the SHA-256 fingerprint of the signing key once the Android package for `marea-ott-demo` is generated.

## Demo

- [marea-ott-demo](https://mauromateus.github.io/marea-ott-demo/)
