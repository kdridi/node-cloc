# node-cloc
Count Lines of Code Library do Node.JS

[Site](https://github.com/kdridi/node-cloc/) |
[Package](https://www.npmjs.com/package/node-cloc)

The [node-cloc](https://lodash.com/) library counts the number of lines of code for the given folder. This library is based on the fatastic [cloc](https://github.com/AlDanial/cloc) tool.

## Installation

```shell
$ npm i node-cloc
```

## Usage

```js
const cloc = require('node-cloc')

cloc('/my/folder').then((res) => console.log(res), (err) => console.log(err))
```