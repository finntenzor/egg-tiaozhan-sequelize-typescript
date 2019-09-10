# egg-tiaozhan-sequelize-typescript

[![NPM version][npm-image]][npm-url]
[![build status][travis-image]][travis-url]
[![Test coverage][codecov-image]][codecov-url]
[![David deps][david-image]][david-url]
[![Known Vulnerabilities][snyk-image]][snyk-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/egg-tiaozhan-sequelize-typescript.svg?style=flat-square
[npm-url]: https://npmjs.org/package/egg-tiaozhan-sequelize-typescript
[travis-image]: https://img.shields.io/travis/eggjs/egg-tiaozhan-sequelize-typescript.svg?style=flat-square
[travis-url]: https://travis-ci.org/eggjs/egg-tiaozhan-sequelize-typescript
[codecov-image]: https://img.shields.io/codecov/c/github/eggjs/egg-tiaozhan-sequelize-typescript.svg?style=flat-square
[codecov-url]: https://codecov.io/github/eggjs/egg-tiaozhan-sequelize-typescript?branch=master
[david-image]: https://img.shields.io/david/eggjs/egg-tiaozhan-sequelize-typescript.svg?style=flat-square
[david-url]: https://david-dm.org/eggjs/egg-tiaozhan-sequelize-typescript
[snyk-image]: https://snyk.io/test/npm/egg-tiaozhan-sequelize-typescript/badge.svg?style=flat-square
[snyk-url]: https://snyk.io/test/npm/egg-tiaozhan-sequelize-typescript
[download-image]: https://img.shields.io/npm/dm/egg-tiaozhan-sequelize-typescript.svg?style=flat-square
[download-url]: https://npmjs.org/package/egg-tiaozhan-sequelize-typescript

## 参考

[https://github.com/xvsuper/ts-egg-sequelize](https://github.com/xvsuper/ts-egg-sequelize)

## 依赖说明

### 依赖的 egg 版本

egg-tiaozhan-sequelize-typescript 版本 | egg 2.x
--- | ---
2.x | 😁
1.x | ❌
0.x | ❌

## 开启插件

```js
// config/plugin.js
exports.sequelize = {
  enable: true,
  package: 'egg-tiaozhan-sequelize-typescript',
};
```

## 使用场景

- Why and What: 如果你想用sequelize-typescript并且还想要完整的类型提示
- How: 开启插件，并在配置里面引入sequelize-typescript

## 详细配置

```js
import { Sequelize } from 'sequelize-typescript';

config.sequelize = {
  Sequelize, // 这里一定要写上
  dialect: 'mysql',
  host: '127.0.0.1',
  port: 3306,
  username: 'root',
  password: '',
  database: 'egg',
}
```

## 如何使用

[https://github.com/RobinBuschmann/sequelize-typescript](https://github.com/RobinBuschmann/sequelize-typescript)

## 提问交流

请直接提PR

## License

[MIT](LICENSE)
