<h1 align="center">
  commitlint-config-pixelmatters
</h1>

<h3 align="center">
  An CommitLint config standard for Pixelmatters projects
</h3>

<p align="center">
This is a CommitLint config that you can use in your projects.
</p>

<p align="center">
  <a href="https://github.com/Pixelmatters/commitlint-config-pixelmatters/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="commitlint-config-pixelmatters is released under the MIT license." />
  </a>
  <a href="https://www.npmjs.com/package/@pixelmatters/commitlint-config-pixelmatters">
    <img src="https://img.shields.io/npm/v/@pixelmatters/commitlint-config-pixelmatters.svg" alt="Current npm package version." />
  </a>
  <a href="https://github.com/Pixelmatters/commitlint-config-pixelmatters/blob/master/CONTRIBUTING.md">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome!" />
  </a>
  <a href="https://twitter.com/intent/follow?screen_name=pixelmatters_">
    <img src="https://img.shields.io/twitter/follow/pixelmatters_.svg?label=Follow%20@pixelmatters_" alt="Follow @pixelmatters_" />
  </a>
</p>

## 🚀 Get Up and Running

You can install this package using either **npm** or **yarn**.

### **Yarn**

If using Yarn:

1. Install the package as a development dependency:

```shell
yarn add @pixelmatters/commitlint-config-pixelmatters --dev
```


### **NPM**

If using NPM:

1. Install the package as a development dependency:

```shell
npm install @pixelmatters/commitlint-config-pixelmatters --save-dev
```

### Install commitizen if it's not already installed
- Great guide on pixelmatters basecamp: https://www.notion.so/pixelmatters/Conventional-Commits-Dynamic-Changelog-3138a2ce8ff343229125fd6f3144f395


### Create a config file
1. Create an `.commitlint.config.js`  file in the root of your project and add the following code:
``` js
module.exports = {
  extends: ['@pixelmatters/commitlint-config-pixelmatters'],
};
```

At this point you should be good to go 👍

## 🤝 How to Contribute

Whether you're helping us fix bugs, improve the docs, or spread the word, thank you! 💪 🧡

Check out our [**Contributing Guide**](https://github.com/Pixelmatters/commitlint-config-pixelmatters/blob/master/CONTRIBUTING.md) for ideas on contributing and setup steps.

## :memo: License

Licensed under the [MIT License](./LICENSE). Based on config-conventional: https://github.com/conventional-changelog/commitlint/tree/master/%40commitlint/config-conventional