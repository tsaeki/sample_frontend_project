# Sample Frontend Project

## Create project and test run
```
# create node project
$ mkdir sample_frontend_project
$ cd sample_frontend_project
$ npm init

# install webpack
$ npm install webpack webpack-cli --save-dev

# create webpack project
$ npx webpack init
```

## Run dev
```
$ npm run start

> sample_frontend_project@1.0.0 start /home/tsaeki/Develop/test_sample_project
> webpack-dev-server

10% building 1/1 modules 0 activeℹ ｢wds｣: Project is running at http://localhost:8080/
ℹ ｢wds｣: webpack output is served from /
ℹ ｢wds｣: Content not from webpack is served from /home/tsaeki/Develop/test_sample_project
ℹ ｢wdm｣: Hash: c71d26d2753aff64ff9b
Version: webpack 4.40.2
Time: 1149ms
Built at: 09/15/2019 11:19:38 AM
                       Asset       Size  Chunks                         Chunk Names
                  index.html  201 bytes          [emitted]
main.1e1096312fa9c9e6c3f8.js    360 KiB    main  [emitted] [immutable]  main
Entrypoint main = main.1e1096312fa9c9e6c3f8.js
[0] multi (webpack)-dev-server/client?http://localhost:8080 ./src/index.js 40 bytes {main} [built]
[./node_modules/ansi-html/index.js] 4.16 KiB {main} [built]
[./node_modules/ansi-regex/index.js] 135 bytes {main} [built]
[./node_modules/html-entities/index.js] 231 bytes {main} [built]
[./node_modules/loglevel/lib/loglevel.js] 7.68 KiB {main} [built]
[./node_modules/strip-ansi/index.js] 161 bytes {main} [built]
[./node_modules/webpack-dev-server/client/index.js?http://localhost:8080] (webpack)-dev-server/client?http://localhost:8080 4.29 KiB {main} [built]
[./node_modules/webpack-dev-server/client/overlay.js] (webpack)-dev-server/client/overlay.js 3.51 KiB {main} [built]
[./node_modules/webpack-dev-server/client/socket.js] (webpack)-dev-server/client/socket.js 1.53 KiB {main} [built]
[./node_modules/webpack-dev-server/client/utils/createSocketUrl.js] (webpack)-dev-server/client/utils/createSocketUrl.js 2.85 KiB {main} [built]
[./node_modules/webpack-dev-server/client/utils/log.js] (webpack)-dev-server/client/utils/log.js 964 bytes {main} [built]
[./node_modules/webpack-dev-server/client/utils/reloadApp.js] (webpack)-dev-server/client/utils/reloadApp.js 1.59 KiB {main} [built]
[./node_modules/webpack-dev-server/client/utils/sendMessage.js] (webpack)-dev-server/client/utils/sendMessage.js 402 bytes {main} [built]
[./node_modules/webpack/hot sync ^\.\/log$] (webpack)/hot sync nonrecursive ^\.\/log$ 170 bytes {main} [built]
[./src/index.js] 48 bytes {main} [built]
    + 18 hidden modules
Child html-webpack-plugin for "index.html":
     1 asset
    Entrypoint undefined = index.html
    [./node_modules/html-webpack-plugin/lib/loader.js!./node_modules/html-webpack-plugin/default_index.ejs] 376 bytes {0} [built]
    [./node_modules/lodash/lodash.js] 528 KiB {0} [built]
    [./node_modules/webpack/buildin/global.js] (webpack)/buildin/global.js 472 bytes {0} [built]
    [./node_modules/webpack/buildin/module.js] (webpack)/buildin/module.js 497 bytes {0} [built]
ℹ ｢wdm｣: Compiled successfully.

```

## Build
```
$ npm run build

> sample_frontend_project@1.0.0 build /home/tsaeki/Develop/test_sample_project
> webpack

Hash: c8dc8a8748792af6769b
Version: webpack 4.40.2
Time: 630ms
Built at: 09/15/2019 11:20:58 AM
                       Asset       Size  Chunks                         Chunk Names
                  index.html  201 bytes          [emitted]
main.55d8ca80f289d8387835.js   3.82 KiB    main  [emitted] [immutable]  main
Entrypoint main = main.55d8ca80f289d8387835.js
[./src/index.js] 48 bytes {main} [built]
Child html-webpack-plugin for "index.html":
     1 asset
    Entrypoint undefined = index.html
    [./node_modules/webpack/buildin/global.js] (webpack)/buildin/global.js 472 bytes {0} [built]
    [./node_modules/webpack/buildin/module.js] (webpack)/buildin/module.js 497 bytes {0} [built]
        + 2 hidden modules
```

# Reference
https://webpack.js.org/concepts/