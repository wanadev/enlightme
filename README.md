# Enlight'me

[![Lint and test](https://github.com/wanadev/enlightme/actions/workflows/tests.yml/badge.svg)](https://github.com/wanadev/enlightme/actions/workflows/tests.yml)
[![NPM Version](http://img.shields.io/npm/v/enlightme.svg?style=flat)](https://www.npmjs.com/package/enlightme)
[![License](http://img.shields.io/npm/l/enlightme.svg?style=flat)](https://github.com/wanadev/enlightme/blob/master/LICENSE)
[![Discord](https://img.shields.io/badge/chat-Discord-8c9eff?logo=discord&logoColor=ffffff)](https://discord.gg/BmUkEdMuFp)


> Enlighten your users with a beautiful documentation

**Enlight'me** is a static site generator based on [Metalsmith][] that let you
build pretty Github pages for your projects without hassles. Just put some Markdown
files in a `doc/` folder of your repo, and you'r done!

[Metalsmith]: http://www.metalsmith.io/


## Install

To install Enlight'me, run the following command:

    npm install --save-dev enlightme


## Documentation

* See https://wanadev.github.io/enlightme/


## Contributing

### Questions

If you have any question, you can:

* [Open an issue on GitHub][gh-issue]
* [Ask on discord][discord]

### Bugs

If you found a bug, please [open an issue on Github][gh-issue] with as much information as possible.

### Pull Requests

Please consider [filing a bug][gh-issue] before starting to work on a new feature. This will allow us to discuss the best way to do it. This is of course not necessary if you just want to fix some typo or small errors in the code.

### Codding Style / Lint

To check codding style, run the follwoing command:

    npm run lint

[gh-issue]: https://github.com/wanadev/enlightme/issues
[discord]: https://discord.gg/BmUkEdMuFp


## Changelog

* **[NEXT]** (changes on master that have not been released yet):

    * Nothing yet ;)

* **v0.2.0:**

    * Added a lint command in package.json (@flozz)
    * Fixed wrong dependencies: added missing lodash, and removed unnecessary request lib (@jbghoul, #7)
    * Updated dependencies (@jbghoul, #7)

* **v0.1.1:**

    * Fixed a syntax error in a template (@flozz)

* **v0.1.0:**

    * Initial release
