# @code-collabo/node-mongo-cli
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-11-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

[![npm version](https://badge.fury.io/js/@code-collabo%2Fnode-mongo-cli.svg)](https://badge.fury.io/js/@code-collabo%2Fnode-mongo-cli) [![Npm package total downloads](https://badgen.net/npm/dt/@code-collabo/node-mongo-cli?color=blue)](https://npmjs.com/package/@code-collabo/node-mongo-cli) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://code-collabo.gitbook.io/node-mongo-v2.0.0/contribution-guide/node-mongo) [![CLI license: AGPL 3.0](https://img.shields.io/badge/CLI%20licence-AGPL%203.0-blue)](https://github.com/code-collabo/node-mongo-cli/blob/develop/LICENSE) [![API boilerplate templates license: ISC](https://img.shields.io/badge/API%20templates%20licence-ISC-blue)](https://github.com/code-collabo/node-mongo-api-boilerplate-templates/blob/develop/LICENSE) [![GitHub issues](https://img.shields.io/github/issues/code-collabo/node-mongo?color=red)](https://github.com/code-collabo/node-mongo/issues) [![GitHub pull requests](https://img.shields.io/github/issues-pr/code-collabo/node-mongo-cli?color=goldenrod)](https://github.com/code-collabo/node-mongo-cli/pulls)

<!-- [![NPM Downloads](https://img.shields.io/npm/dy/@code-collabo/node-mongo-cli?color=blue)](https://www.npmjs.com/package/@code-collabo/node-mongo-cli) -->

#

> **Note**
>
> node-mongo projects require you to have Node.js or Node Version Manager (NVM) installed on your computer

#

**Supported Node.js versions:** Node.js v16.x to v20.x

#

**Operating Systems:** Mac, Windows, and Linux OS

#

**Parent repo:** [code-collabo/node-mongo](https://github.com/code-collabo/node-mongo)

#
> **Note**
>
> The latest version of CLI generates API boilerplate templates v1.0.0

#

The [node-mongo-cli](https://www.npmjs.com/package/@code-collabo/node-mongo-cli) is a Command Line Interface made with Node.js. It bootstraps any of the [node-mongo API boilerplate templates](https://github.com/code-collabo/node-mongo-api-boilerplate-templates) for your nodejs mongoDB development, depending on your preference.

### Features

![node-mongo](https://github.com/Ifycode/Ifycode/blob/main/code-collabo/node-mongo-cli.gif?raw=true)

#### CLI

* CLI bootstraps the typescript, es module, or common js (a.k.a. ts, esm, cjs) templates for nodejs mongoDB development.
* Install dependencies and initialize git for the template bootstrapped or choose to skip them.
* Folders are automatically created based on user entry in the prompt or command line.
* The default folder name is used and incremented if the folder name provided already exists.

#### API boilerplate templates

* API boilerplate templates now use the MVC architecture pattern i.e. separated route, model, controller, and service files.
* Development environment already set up with @babel (for esm template only), eslint, and server watch.
* The default connection setup type is MongoDB Atlas. You get to choose if you want to use Atlas or switch to the Local mongoDB connection setup type, and you also get to save your preferred connection setup type for when next you run the automated development server.
* Improved user experience with the newly added walk-through prompts in the terminal: quick to setup, easy to use, with automated and improved user support.

### CLI installation
Install CLI globally with this command:
````
npm install -g @code-collabo/node-mongo-cli
````

### CLI command
After installing globally, use the node-mongo command.
````
node-mongo
````

### CLI usage
````
node-mongo <folder_name> <template>
````

### CLI usage example

Replace \<folder\_name> with your preferred folder name. Replace \<template> with any of these: ts, esm, or cjs. The example below will bootstrap the ts template i.e. the typescript template into a folder named test-folder.

```
node-mongo test-folder ts
```

### API boilerplate template and automated development server

See the [API boilerplate templates documentation](https://code-collabo.gitbook.io/node-mongo-v2.0.0/api-boilerplate-templates) for detailed steps to setup your generated API boilerplate template, run the automated development server, and build your own mongoDB backend application with it.

### Show CLI help
````
node-mongo --help
````

### CLI flags
````
-h, --help          Show help
-v, --version       Show version number
-i, --install       Install dependencies
-g, --git           Initialize git repo
-s, --skip-install  Skip installing dependencies
-x, --skip-git      Skip initializing git
-y, --yes           No prompt: See note on --yes flag below
````

### CLI prompts
If you do not specify one or both arguments above,
you will be prompted to add your folder name and/or
choose template option from list. For foldername, you
can choose to use the default foldername provided in
the prompt or type in your preferred folder name.

### CLI skip prompts
No prompt when --yes flag is used. It skips both install
and git init. The CLI will generate the (default) ts template
if no template is specified or if the template entered is not
in the template collection. In the case of folder name, default
foldername is used if no folder name is specified or when the
folder name used already exists.

## Documentation
See the links to the official documentation of the node-mongo project and community building it below:
- [Node Mongo documentation](https://code-collabo.gitbook.io/node-mongo-v2.0.0)
- [Code Collabo documentation](https://code-collabo.gitbook.io/community-doc-v1.0.0)

## Appreciation
Appreciation to [@dkundel](https://github.com/dkundel), [@academind](https://github.com/academind), [@CodAffection](https://github.com/CodAffection), [@coryhouse](https://github.com/coryhouse) for the awesome helpful course resources they create, and to [@jiobiagba](https://github.com/jiobiagba) and [@IsraelObiagba](https://github.com/IsraelObiagba) for their occasional but mighty contributions.

<table>
  <tr>
    <td align="center"><a href="https://dkundel.com"><img src="https://avatars.githubusercontent.com/u/1505101?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Dominik Kundel</b></sub></a><br /><a href="#mentoring-dkundel" title="Mentoring">🧑‍🏫</a></td>
    <td align="center"><a href="https://academind.com"><img src="https://avatars.githubusercontent.com/u/28806202?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Academind</b></sub></a><br /><a href="#mentoring-academind" title="Mentoring">🧑‍🏫</a></td>
    <td align="center"><a href="http://codaffection.com/"><img src="https://avatars.githubusercontent.com/u/32505654?v=4?s=100" width="100px;" alt=""/><br /><sub><b>CodAffection</b></sub></a><br /><a href="#mentoring-CodAffection" title="Mentoring">🧑‍🏫</a></td>
    <td align="center"><a href="http://www.bitnative.com"><img src="https://avatars.githubusercontent.com/u/1688997?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Cory House</b></sub></a><br /><a href="#mentoring-coryhouse" title="Mentoring">🧑‍🏫</a></td>
    <td align="center"><a href="https://github.com/jiobiagba"><img src="https://avatars.githubusercontent.com/u/42423547?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Joseph Obiagba</b></sub></a><br /><a href="#mentoring-jiobiagba" title="Mentoring">🧑‍🏫</a></td>
    <td align="center"><a href="https://github.com/IsraelObiagba"><img src="https://avatars.githubusercontent.com/u/14045379?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Israel Obiagba</b></sub></a><br /><a href="#mentoring-IsraelObiagba" title="Mentoring">🧑‍🏫</a></td>
  </tr>
</table>

## Contributors ✨

Thanks to these amazing contributors to the node-mongo-cli project. This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. See [emoji key](https://allcontributors.org/docs/en/emoji-key). Contributions of any kind welcome!

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/Sync271"><img src="https://avatars.githubusercontent.com/u/67158080?v=4?s=100" width="100px;" alt="Abhishek K M"/><br /><sub><b>Abhishek K M</b></sub></a><br /><a href="https://github.com/code-collabo/node-mongo-cli/commits?author=Sync271" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://allcontributors.org"><img src="https://avatars.githubusercontent.com/u/46410174?v=4?s=100" width="100px;" alt="All Contributors"/><br /><sub><b>All Contributors</b></sub></a><br /><a href="#infra-all-contributors" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
      <td align="center" valign="top" width="16.66%"><a href="http://chuddyjoachim.com"><img src="https://avatars.githubusercontent.com/u/56943504?v=4?s=100" width="100px;" alt="Chikezie Joachim"/><br /><sub><b>Chikezie Joachim</b></sub></a><br /><a href="https://github.com/code-collabo/node-mongo-cli/commits?author=chuddyjoachim" title="Code">💻</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/Dkingofcode"><img src="https://avatars.githubusercontent.com/u/91491738?v=4?s=100" width="100px;" alt="David Oladepo"/><br /><sub><b>David Oladepo</b></sub></a><br /><a href="https://github.com/code-collabo/node-mongo-cli/commits?author=Dkingofcode" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="16.66%"><a href="http://hritikr.me"><img src="https://avatars.githubusercontent.com/u/35923605?v=4?s=100" width="100px;" alt="Hritik R"/><br /><sub><b>Hritik R</b></sub></a><br /><a href="https://github.com/code-collabo/node-mongo-cli/commits?author=HritikR" title="Documentation">📖</a> <a href="https://github.com/code-collabo/node-mongo-cli/commits?author=HritikR" title="Code">💻</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://keithanphilander-e53b5c.netlify.app/"><img src="https://avatars.githubusercontent.com/u/29425128?v=4?s=100" width="100px;" alt="Keithan Philander"/><br /><sub><b>Keithan Philander</b></sub></a><br /><a href="https://github.com/code-collabo/node-mongo-cli/issues?q=author%3AKeithanPhilander" title="Bug reports">🐛</a> <a href="https://github.com/code-collabo/node-mongo-cli/commits?author=KeithanPhilander" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/izhar360"><img src="https://avatars.githubusercontent.com/u/79567009?v=4?s=100" width="100px;" alt="Muhammad Izhar"/><br /><sub><b>Muhammad Izhar</b></sub></a><br /><a href="https://github.com/code-collabo/node-mongo-cli/commits?author=izhar360" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/Ifycode"><img src="https://avatars.githubusercontent.com/u/45185388?v=4?s=100" width="100px;" alt="Obiagba Mary Ifeoma"/><br /><sub><b>Obiagba Mary Ifeoma</b></sub></a><br /><a href="https://github.com/code-collabo/node-mongo-cli/commits?author=Ifycode" title="Code">💻</a> <a href="https://github.com/code-collabo/node-mongo-cli/commits?author=Ifycode" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://github.com/samuko-things"><img src="https://avatars.githubusercontent.com/u/75276934?v=4?s=100" width="100px;" alt="Obiagba Samuel"/><br /><sub><b>Obiagba Samuel</b></sub></a><br /><a href="https://github.com/code-collabo/node-mongo-cli/commits?author=samuko-things" title="Code">💻</a> <a href="https://github.com/code-collabo/node-mongo-cli/issues?q=author%3Asamuko-things" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="16.66%"><a href="https://olaleye.vercel.app/"><img src="https://avatars.githubusercontent.com/u/70102539?v=4?s=100" width="100px;" alt="Olaleye Blessing"/><br /><sub><b>Olaleye Blessing</b></sub></a><br /><a href="https://github.com/code-collabo/node-mongo-cli/commits?author=Olaleye-Blessing" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="16.66%"><a href="http://rashidmya.dev"><img src="https://avatars.githubusercontent.com/u/64389512?v=4?s=100" width="100px;" alt="Rashid"/><br /><sub><b>Rashid</b></sub></a><br /><a href="https://github.com/code-collabo/node-mongo-cli/commits?author=rashidmya" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
