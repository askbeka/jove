# jove
Modern "webby" framework

## Motivation

`package.json, package-lock.json, .editorconfig, .eslintrc, eslintignore, npmrc, .npmignore, bowerrc, husky.config, prettier.config, prettierignore, karma.config, jest.config, webpack.config, commitlint.config, .gitignore, browserlistrc, .etc`.
Those files are a part of a sandard setup of a modern front end project, none of those are actual product code. Those tools are there for a reason and they are absolutely amazing, but.. so much noise:(

Modern browsers have native modules, there are solutions like unpkg.com that allow to fetch a dependency without a need for a package manager. Solutions like plunkr, jsbin, stackblitz etc., have been showning that you can develop just in browser.
Many organisations, teams usually agree on one way of configuring projects.

Main goal of this tool is to reduce amount of noise and help enginners focus on their product, by utilising future proof solutions and ideas.
