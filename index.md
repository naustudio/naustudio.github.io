---
title: NAU Code - Nau Studio code documentation hub
image:
  path: /cover.png
  height: 339
  width: 576
---
Welcome to Nau Code, collection of conventions, workflows documentation and open source projects by [Nau Studio](https://nautud.io) team.

## Conventions

- [JavaScript Style Guide](https://naustudio.github.io/javascript/)
  - ESLint config [Nau Base](https://www.npmjs.com/package/eslint-config-nau)
  - ESLint config [Nau React projects](https://www.npmjs.com/package/eslint-config-nau-react)
- [HTML & CSS Code Guide](https://naustudio.github.io/code-guide/)

## Working Environment Configuration

- [Nau dotfiles](https://github.com/naustudio/dotfiles) for:
  + macOS
  + VSCode _(our current preferred code editor)_
  + Sublime Text 3

- [Yeoman NauJS Generators](https://www.npmjs.com/package/generator-naujs):
  + Install: `npm install --global yo generator-naujs`
  + Generators:
    - `yo naujs`: NAU 2017 project workflow setup
    - `yo naujs:gulp`: generate basic gulpfile and install its dependencies
    - `yo naujs:gulp-iconfont`: add gulp iconfont task and install its dependencies
    - `yo naujs:dotfiles`: add dotfiles config for projects (can be used alone)

## Open Source

- [__node-vn-payments__](https://github.com/naustudio/node-vn-payments) [![npm version](https://img.shields.io/npm/v/vn-payments.svg)](https://www.npmjs.com/package/vn-payments): NodeJS library to support building checkout URL for Vietnam-based online payment gateways.
  + [API Documentation](https://code.naustud.io/node-vn-payments/)
  + [Demo site](https://vn-payments-demo.now.sh/)
- [Nau's Modified __Keystone CMS__](https://github.com/naustudio/keystone) [![npm version](https://img.shields.io/npm/v/@naustudio/keystone.svg)](https://www.npmjs.com/package/@naustudio/keystone): A modified version of Keystone to support multi language, new local image field... Note: documentation is needed.
- [__Nau Jukebox__](https://github.com/naustudio/nau-jukebox): Meteor web app, online jukebox (songs from Youtube, Soundcloud, NCT...)
  + [Live Site](https://jukebox.naustud.io)
- [__Nau Tab__](https://github.com/trongthanh/nau-chrome-tab): Chrome new tab alternative
  + [Web Store](https://chrome.google.com/webstore/detail/nau-tab/pimockeojlggmlnknhicajgckmlggifa?hl=en)
  + [Landing Page](https://naustud.io/start)
- [__Tech Stack__](https://github.com/naustudio/techstack): Nau tech stack forced diagram using D3 & SVG
  + [Live Site](https://naustud.io/tech-stack/)
- [__Banh Chung Xanh__](https://github.com/naustudio/banh-chung-xanh): Meteor web app, sokoban-like online game
  + [Live site](https://banhchungxanh.naustud.io/vi)
- [__Info to Speech__](https://github.com/trongthanh/info-to-speech), code name 'chị Ba': weather forecast and care talks which is spoken out loud with synthesized Vietnamese speech from Google TTS.
