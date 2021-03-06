# Placa

[![NPM version][npm-img]][npm]
[![Build Status][ci-img]][ci]
[![Coverage Status][coveralls-img]][coveralls]
[![Dependency Status][dep-img]][dep]
[![devDependency Status][devDep-img]][devDep]

[![XO code style][xo-img]][xo]
[![Greenkeeper badge][greenkeeper-img]][greenkeeper]


[npm-img]:         https://img.shields.io/npm/v/@tadashi/placa.svg
[npm]:             https://www.npmjs.com/package/@tadashi/placa
[ci-img]:          https://travis-ci.org/lagden/placa.svg
[ci]:              https://travis-ci.org/lagden/placa
[coveralls-img]:   https://coveralls.io/repos/github/lagden/placa/badge.svg?branch=master
[coveralls]:       https://coveralls.io/github/lagden/placa?branch=master
[dep-img]:         https://david-dm.org/lagden/placa.svg
[dep]:             https://david-dm.org/lagden/placa
[devDep-img]:      https://david-dm.org/lagden/placa/dev-status.svg
[devDep]:          https://david-dm.org/lagden/placa#info=devDependencies
[xo-img]:          https://img.shields.io/badge/code_style-XO-5ed9c7.svg
[xo]:              https://github.com/sindresorhus/xo
[greenkeeper-img]: https://badges.greenkeeper.io/lagden/placa.svg
[greenkeeper]:     https://greenkeeper.io/


Consulta de placas de veículos na base de dados do SINESP Cidadão  
Inspirado [nesse](https://github.com/victor-torres/sinesp-client) projeto feito em Python


## Instalação

```
$ npm i -S @tadashi/placa
```


## Uso

```js
const consulta = require('@tadashi/placa');

consulta('GKC3998').then(r => {
  console.log(r.modelo) // FIAT/MOBI EASY ON
})
```


### API

#### consulta(placa)

Nome        | Tipo                 | Requerido | Default           | Descrição
----------- | -------------------- |:---------:|:-----------------:| ------------
placa       | string               | sim       | -                 | Placa do veículo


## License

MIT © [Thiago Lagden](http://lagden.in)
