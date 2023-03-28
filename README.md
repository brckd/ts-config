# @bricked/ts-config

[![license](https://img.shields.io/github/license/brycked/ts-config)](LICENSE.md)
[![semantic-release: angular](https://img.shields.io/badge/semantic--release-angular-e10079?logo=semantic-release)](https://github.com/semantic-release/semantic-release)
[![version](https://img.shields.io/npm/v/@bricked/ts-config?color=crimson&logo=npm)](https://www.npmjs.com/package/@bricked/ts-config)

Shared typescript configuration for my projects.

## Installation

```sh
npm install @bricked/ts-config
yarn add @bricked/ts-config
pnpm add @bricked/ts-config
```

## Usage

You can use [`tsconfig.json`](./tsconfig.json) by extending it in yours:

```json
{
  "extends": "@bricked/ts-config"
}
```

This is a config suited for nearly all projects, but you may extend it with your own config options.
