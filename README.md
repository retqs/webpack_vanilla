# webpack_vanilla
Won't work at all, it's just throwing 

ERROR in ./src/styles/main.scss (./node_modules/css-loader/dist/cjs.js!./node_modules/sass-loader/dist/cjs.js!./src/styles/main.scss)
Module build failed (from ./node_modules/sass-loader/dist/cjs.js):
Error: Node Sass version 6.0.1 is incompatible with ^4.0.0.
    at getSassImplementation (/Users/danylo.yahoda/Desktop/pomoika/playground/node_modules/sass-loader/dist/getSassImplementation.js:46:13)
    at Object.loader (/Users/danylo.yahoda/Desktop/pomoika/playground/node_modules/sass-loader/dist/index.js:40:61)
 @ ./src/styles/main.scss 2:26-135 53:4-74:5 56:18-127
 @ ./src/index.js
Child html-webpack-plugin for "index.html":
     1 asset
    Entrypoint undefined = index.html
    [./node_modules/html-webpack-plugin/lib/loader.js!./src/index.html] 1.81 KiB {0} [built]
ℹ ｢wdm｣: Failed to compile.

the issue belongs to web-packdev server and node sass
