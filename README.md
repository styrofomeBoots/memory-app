# Memory App

## Store your memories and photos in an app built with Ionic and Vue.js

### Overview

An Ionic app that stores memory details and an image url or camera photo and displays them in a list as clickable components that will show full details when selected.

[Built using this Academind's tutorial.](https://youtu.be/mQ4zmFy4d7Y)

### Notes

- To ensure camera features are available on desktop or PWAs, custom PWA elements must be imported.
  - Install pwa-elements through the CLI by entering `npm install @ionic/pwa-elements`.
  - Import custom elements in main.js/main.ts using `import { defineCustomElements } from '@ionic/pwa-elements/loader';`.
  - add `defineCustomElements(window);` to `router.isReady()` in main.js/main.ts.
- Capacitor plugin must be added to the project to allow Android and iOS builds.
- Commenting `es-lint-disable-next-line` will force eslint to ignore the following line.
