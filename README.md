# rawnooncode

A raw, minified production JavaScript bundle — not hand-written source.

## What's in here

`js.txt` is a single ~23,000-line minified/bundled JS file (the kind of output you'd get from a Vite/webpack/Rollup build). From the bundled license headers and code shape, it includes a bundled copy of **React** plus application code, all concatenated and minified together — consistent with the production build of a web app (referenced elsewhere as related to `noonhack.online`).

## Important caveats

- This is **build output**, not source code — variable names are mangled, modules are inlined, and there's no meaningful project structure to document (no `package.json`, no component tree, no readable source files).
- Because it's minified, there isn't much to usefully describe beyond "this is a bundled front-end app." If you want a README that actually documents functionality, it'll need to point at the *source* repo/branch this was built from, not this extracted bundle.

## Suggested next step

If this was meant to preserve a working copy of a site's client bundle (e.g. for reference or recovery), consider also committing the original (un-minified) source and build config, so future-you (or anyone else) can actually read and modify the code.
