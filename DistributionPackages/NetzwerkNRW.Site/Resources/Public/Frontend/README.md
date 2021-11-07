# Neos website frontend

To start developing:

```sh
cd DistributionPackages/NetzwerkNRW.Site/Resources/Public/Frontend
npm install
npm start
```

As long as `npm start` is running, it will **watch** your changes. You can edit `_sass/main.scss` and `_javascript/main.js` at will. Changes are **immediately** compiled to their destinations.

Some controlling output is written to the `npm start` console in that process:

```sh
_javascript/main.js -> lib/main.js

=> changed: .../DistributionPackages/NetzwerkNRW.Site/Resources/Public/Frontend/_sass/main.scss
Rendering Complete, saving .css file...
Wrote CSS to .../DistributionPackages/NetzwerkNRW.Site/Resources/Public/Frontend/css/main.css
```
