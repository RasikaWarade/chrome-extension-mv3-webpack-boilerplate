# Chrome Extension Manifest Version 3 + Webpack  ( Boilerplate Code )

This Chrome Extension boilerplate uses Webpack to speed up the process of writing modular Javascript code, loading HTML and CSS easily, and re-rendering the browser based on changes.

## Why?

As per [Chrome Extension Timeline](https://developer.chrome.com/docs/extensions/mv3/mv2-sunset/), all the extensions supporting Manifest Version v2 are sunsetting  in Jan 2023 and for new extensions it is now a hard requirement to move to Manifest Version V3.

The important security change from the recent release of Chrome Extension Manifest Version v3 is that [remotely hosted code](https://developer.chrome.com/docs/extensions/mv3/intro/mv3-overview/#remotely-hosted-code) like Javascript is not allowed. This will cause a problem if your codebase for extension is not bundled and structured in a modular fashion. Definately, it is a problem for a begineer like me and there is no guideline I could find to build that setup. Also I was new to webpack when I started working on building my own Chrome Extension, so I believe most of the new beginners will hit this problem.



Install Setup Done Webpack and webpack bundles 

`npm install --save-dev webpack webpack-cli html-webpack-plugin clean-webpack-plugin copy-webpack-plugin`


Commands

1. Run `npm install`
2. Run `npm run build`
3. Run `npm run release`
