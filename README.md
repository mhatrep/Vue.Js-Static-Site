# Vue.Js-Static-Site
Vue.js Static Website

----------------------------------------------------
also read More About JAMStack : https://jamstack.org/
----------------------------------------------------

## Assuming you have installed npm / node.js

----------------------------------------------------

$ npm install vue-cli -g

## Create Project
$ vue init nuxt/starter PrashantMhatre

----------------------------------------------------

? Project name mywebsite
? Project description Nuxt.js project
? Author

   vue-cli · Generated "PrashantMhatre".

   To get started:

     cd PrashantMhatre
     npm install # Or yarn
     npm run dev

----------------------------------------------------
mhatr@LAPTOP c:\vue
$ cd PrashantMhatre

mhatr@LAPTOP c:\vue\PrashantMhatre
$ npm install
[ .................] - fetchMetadata: sill pacote range manifest for widest-line@^3.1.0 fetched in 403ms


----------------------------------------------------
$ npm run dev

# Visit: http://localhost:3000/

## Generate a static site 
$ npm run generate

----------------------------------------------------

mhatr@LAPTOP c:\vue\PrashantMhatre
$ npm run generate

> mywebsite@1.0.0 generate c:\vue\PrashantMhatre
> nuxt generate

i Production build                                                                                                                                                                   20:54:48
√ Builder initialized                                                                                                                                                                20:54:48
√ Nuxt files generated                                                                                                                                                               20:54:48

√ Client
  Compiled successfully in 5.08s

√ Server
  Compiled successfully in 1.14s


Hash: feb64ca7fecb8f2f046d
Version: webpack 4.41.2
Time: 5083ms
Built at: 11/02/2019 8:54:54 PM
                         Asset       Size  Chunks                         Chunk Names
../server/client.manifest.json   6.47 KiB          [emitted]
       423d79ec0171b5fdcea3.js   43.8 KiB       0  [emitted] [immutable]  app
       508c4af06130fc544fe4.js   3.71 KiB       2  [emitted] [immutable]  pages_index
       9fc4208b717d64454182.js    148 KiB       1  [emitted] [immutable]  commons.app
                      LICENSES  389 bytes          [emitted]
       c70dcb0472861228fdf1.js   2.31 KiB       3  [emitted] [immutable]  runtime
 + 2 hidden assets
Entrypoint app = c70dcb0472861228fdf1.js 9fc4208b717d64454182.js 423d79ec0171b5fdcea3.js

Hash: 85c2b1a9c551cd6c971b
Version: webpack 4.41.2
Time: 1140ms
Built at: 11/02/2019 8:54:55 PM
                  Asset       Size  Chunks                         Chunk Names
7b4c02e39d070c3d9b7b.js   3.72 KiB       1  [emitted] [immutable]  pages_index
              server.js   25.3 KiB       0  [emitted]              app
   server.manifest.json  145 bytes          [emitted]
Entrypoint app = server.js
i Generating pages                                                                                                                                                                   20:54:55
√ Generated /

----------------------------------------------------

A new directory named ‘dist’ will be generated that contains the static site files (with minified code)


----------------------------------------------------
# mywebsite

> Nuxt.js project

## Build Setup

``` bash
# install dependencies
$ npm install # Or yarn install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout the [Nuxt.js docs](https://github.com/nuxt/nuxt.js).


