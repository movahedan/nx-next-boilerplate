# @nx-starter

![LICENSE](https://img.shields.io/github/license/movahedan/nx-starter?style=flat-square)
![Top language](https://img.shields.io/github/languages/top/movahedan/nx-starter?style=flat-square)
![Downloads](https://img.shields.io/github/downloads/movahedan/nx-starter/total?style=flat-square)
![Pull requests](https://img.shields.io/github/issues-pr/movahedan/nx-starter?style=flat-square)

## Features

- [x] Powered by NX and Yarn workspaces, built for React projects
- [x] Fully TypeScript with production-ready and strict configurations
- [x] Scalable Jest configuration with Fetch, DOM, Match Media, and Accessibility setups
- [x] Powerful eslint integrated with Prettier, TypeScript, Jest, Imports, React, and A11Y configurations
- [x] Strong husky with lint-staged, commitlint, commitizen, and branchlint integrations
- [x] Organized output directory that represents build, coverage, storybook, and tsc
- [x] Conventional release, auto generate-able changelog via Trunked based development for monorepos

## Modules

- [x] Fetcher module on top of fetch, with default configuration and custom event handlers
- [x] Analytics module implementation with react hooks, independent DOM event tracking, and simple tracking
- [x] Media Queries module for making responsive pages in JavaScript with supports for SSR
- [x] Sample React UI library with styled-components, that supports Storybook and Unit testing
- [ ] SWR data layer with generated functions via Orval

## Applications

- [x] Next.js application
- [x] Create react application
- [ ] Add a ReactNative application
- [ ] Add a Nest.js application, or a pure express Back-End application

## TODO

- [ ] Git rebase, Git squash and Merge process
- [ ] GitFlow! Github actions for linting, creating artifacts, and publishing the project
- [ ] Take a look at GraphQL architecture to see if it fits or not
- [ ] Publish some of the modules like Fetcher or Analytics
- [ ] Add some generators since I changed the style of libs/apps

> The general idea about the features and modules has been inspired by other boilerplate of mine [Next boilerplate](https://github.com/movahedan/next-boilerplate)


yarn 2> >(grep -v warning 1>&2)