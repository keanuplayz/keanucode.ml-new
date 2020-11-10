---
layout: layouts/post-sidebar.njk
title: 'Getting Started'
sidebar: travbot
summary: 
eleventyNavigation:
  key: gettingstarted
  title: 'Getting Started'
  parent: travbot
  order: 2
tags:
  - project
  - travbot
---
# Getting Started

1. `npm install`
2. `npm run build`
3. `npm start`

# Getting Started (Developers)

1. `npm install`
2. `npm run dev`
3. Familiarize yourself with the [project's structure](Documentation.md).
4. Make sure to avoid using `npm run build`! This will remove all your dev dependencies (in order to reduce space used). Instead, use `npm run once` to compile and build in non-dev mode.
5. Begin developing.

## Don't forget to...

- ...update the [changelog](CHANGELOG.md) and any other necessary docs.
- ...update the version numbers in `package.json` and `package-lock.json`.
- ...make sure the test suite passes by running `npm test`.