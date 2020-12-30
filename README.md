# odd-gat

A template for GatsbyJS projects.

## Table of Contents

- [External Documents](#external-documents)
- [Milestones](#milestones)
- [Projects](#projects)
- [Quick start](#quick-start)
- [Status](#status)
- [What's included](#whats-included)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Contributing](#contributing)
- [Community](#community)
- [Versioning](#versioning)
- [Creator](#creator)
- [Copyright and license](#copyright-and-license)

## External Documents

- [Contributing](https://github.com/Odd-use/odd-gat/blob/main/CONTRIBUTING.md)
- [Changelog](https://github.com/Odd-use/odd-gat/blob/main/CHANGELOG.md)
- [Wiki](https://github.com/Odd-use/odd-gat/wiki)

## Projects

- [Issues](https://github.com/Odd-use/odd-gat/projects/1)
- [Pull requests](https://github.com/Odd-use/odd-gat/projects/2)
- [Questions](https://github.com/Odd-use/odd-gat/projects/3)

## Milestones

- [Create Frontend Architecture](https://github.com/Odd-use/odd-gat/milestone/1)
- [Create Git Architecture](https://github.com/Odd-use/odd-gat/milestone/5)
- [Set Coding Conventions](https://github.com/Odd-use/odd-gat/milestone/2)
- [Create Content Components](https://github.com/Odd-use/odd-gat/milestone/4)
- [Create Layout Architecture](https://github.com/Odd-use/odd-gat/milestone/3)
- [Create Documentation Architecture](https://github.com/Odd-use/odd-gat/milestone/6)

## Quick start

### Download

Navigate the a directory on your computer were you are working on sites and run this command:

```shell
git clone https://github.com/Odd-use/odd-gat.git
```

### Install packages

Navigate the site’s directory and run this command.

With NPM:

```shell
npm i
```

With Yarn:

```shell
yarn
```

### Start developing

Navigate the site’s directory and start it up. Will be located on url: http://localhost:8000

With Gatsby:

```shell
gatsby develop
```

With NPM:

```shell
npm run develop
```

With Yarn:

```shell
yarn develop
```

### Build the project

Navigate the site’s directory and start it up. Will be located on url: http://localhost:8000

With NPM

```shell
npm run build
```

With Yarn

```shell
yarn build
```

### Develop & Test on Smartphone

Navigate the site’s directory and start it up. Wait until the React-App has fully started and you will find the IP to put in your browser on your smartphone.

### Start Storybook

Navigate the site’s directory and start it up. Will be located on url: http://localhost:6006

```shell
npm run storybook
```

###

| Name                     | Local                 |
| ------------------------ | --------------------- |
| GatsbyJS                 | http://localhost:8000 |
| Storybook: UI Components | http://localhost:6006 |

## Status

[![current release](https://img.shields.io/github/release/Odd-use/odd-gat.svg)](https://img.shields.io/github/release/Odd-use/odd-gat)

[![license](https://img.shields.io/github/license/Odd-use/odd-gat.svg)](https://img.shields.io/github/license/Odd-use/odd-gat)

[![peerDependencies Status](https://img.shields.io/david/peer/Odd-use/odd-gat)](https://david-dm.org/Odd-use/odd-gat?type=peer)

[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

## What's included

### File structure

```text
🗄️ odd-gat
┃
┠── 📁 .github
┃    ├┄┄ 📁 ISSUE_TEMPLATE
┃    └┄┄ 📁 workflows
┃        ├┄┄ 📄 lighthouse-test.yml
┃        └┄┄ 📄 semantic-release.yml
┃
┠── 📁 .storybook
┃
┠── 📁 public
┃   ├┄┄ 📁 fonts
┃   └┄┄ 📄 index.html
┃
┠── 📁 src
┃   ├── 📁 components
┃   │   ├┄┄ 📁 atoms
┃   │   ├┄┄ 📁 molecules
┃   │   ├┄┄ 📁 organisms
┃   │   └┄┄ 📁 templates
┃   ├┄┄ 📁 theme
┃   └┄┄ 📁 pages
┃
┠┄┄ 🪄 .gatsby-config
┠┄┄ 🦔 .browserslistrc
┠┄┄ 🐭 .editorconfig
┠┄┄ 🐺 .huskyrc
┠┄┄ 📝 README.md
┠┄┄ 📝 CONTRIBUTING.md
┠┄┄ 📝 CHANGELOG.md
┠┄┄ 📦 package.json
┖┄┄ 🔒 package-lock.json

```

### Dependencies

I recommended to have these CLI's and dependencies in order to download and install everything without a clitch.

| Logo                                        | Name                                       | Comments                                             |
| ------------------------------------------- | ------------------------------------------ | ---------------------------------------------------- |
| ![Homebrew Logo](docs/img/homebrew.png)     | [Homebrew](https://brew.sh/)               | Package manager (for Mac)                            |
| ![NVM Logo](docs/img/nvm.png)               | [NVM](https://github.com/nvm-sh/nvm)       | Node & NPM Version Manager                           |
| ![NodeJS Logo](docs/img/nodejs.png)         | [NodeJS](https://nodejs.org/)              | JavaScript Runtime Engine                            |
| ![NPMJS Logo](docs/img/npmjs.png)           | [NPMJS](https://www.npmjs.com/)            | Node Page Manager                                    |
| ![Storybook Logo](docs/img/storybookjs.png) | [Storbyook](https://storybook.js.org/)     | UI Component Explorer                                |
| ![Git Logo](docs/img/git.png)               | [Git](https://git-scm.com)                 | Distributed version control system                   |
| ![Markdown Logo](docs/img/markdown.png)     | [Markdown](https://www.markdownguide.org/) | Markup language for formating virtually any document |

### Tech Stack

### Required

The project uses these technologies.

| Logo                                                                                              | Name                                                                      | Category           | Description              |
| ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- | ------------------ | ------------------------ |
| <img src="https://cdn.svgporn.com/logos/html-5.svg" alt="HTML5 Logo" height="48">                 | [HTML5](https://html.spec.whatwg.org/)                                    | Markup             | Language                 |
| <img src="https://cdn.svgporn.com/logos/css-3.svg" alt="CSS3 Logo" height="48" />                 | [CSS3](https://www.w3.org/TR/CSS/)                                        | Styling            | Language                 |
| ![Husky Logo](docs/img/husky.png)                                                                 | [Husky](https://typicode.github.io/husky/)                                | Git                | Message validator        |
| ![Commitlint Logo](docs/img/commitlint.png)                                                       | [Commitlint](https://commitlint.js.org/)                                  | Git                | Linter                   |
| ![Commitizen Logo](docs/img/commitizen.png)                                                       | [Commitizen](https://github.com/commitizen)                               | Git                | Wizard tool for commits  |
| ![Semantic-Release Logo](docs/img/semanticrelease.png)                                            | [Semantic-Release](https://semantic-release.gitbook.io/semantic-release/) | Git                | Versioning tool          |
| <img src="https://cdn.svgporn.com/logos/eslint.svg" alt="" ESLint Logo height="48" />             | [ESLint](https://eslint.org/)                                             | Coding conventions | JavaScript linter        |
| ![EditorConfig Logo](docs/img/editorconfig.png)                                                   | [EditorConfig](https://editorconfig.org/)                                 | Coding conventions | IDE coding styles        |
| <img src="https://cdn.svgporn.com/logos/prettier.svg" alt="Prettier Logo" height="48" />          | [Prettier](https://prettier.io/)                                          | Coding conventions | Code formatter           |
| <img src="https://cdn.svgporn.com/logos/react.svg" alt="ReactJS Logo" height="48" />              | [ReactJS](https://reactjs.org/)                                           | Frontend           | JavaScript library       |
| <img src="https://cdn.svgporn.com/logos/browserslist.svg" alt="Browserslist" height="48" />       | [Browserslist](https://github.com/browserslist)                           | Frontend           | Share targeted browsers  |
| <img src="https://cdn.svgporn.com/logos/material-ui.svg" alt="Material-UI Logo" height="48" />    | [Material-UI](https://material-ui.com)                                    | Frontend           | Design System            |
| <img src="https://cdn.svgporn.com/logos/storybook-icon.svg" alt="StorybookJS Logo" height="48" /> | [Storbyook](https://storybook.js.org/)                                    | Documentation      | UI Component Explorer    |
| <img src="https://cdn.svgporn.com/logos/graphql.svg" alt="GraphQL" height="48" />                 | [GraphQL](http://graphql.org/)                                            | Database           | Query Language for API's |

### Optional

| Logo                                                                                            | Name                                   | Category       | Description                                    |
| ----------------------------------------------------------------------------------------------- | -------------------------------------- | -------------- | ---------------------------------------------- |
| <img src="https://cdn.svgporn.com/logos/chromatic-icon.svg" alt="Chromatic Logo" height="48" /> | [Chromatic](https://www.chromatic.com) | Documentation  | Feedback, Visual testing, & Documentation Tool |
| <img src="https://cdn.svgporn.com/logos/figma.svg" alt="Figma" height="48" />                   | [Figma](https://www.figma.com)         | Design         | Graphical Design Tool                          |
| <img src="https://cdn.svgporn.com/logos/docker-icon.svg" alt="Docker" height="48" />            | [Docker](https://www.docker.com/)      | Virtualization | Container Platform                             |

### Design Pattern

All components, templates & pages are trying to follow the [Atomic Design Methodology](https://github.com/Odd-use/odd-gat/blob/main/DESIGN.md)

## Community

- [Website](https://www.odduse.com/)
- <a href="https://www.instagram.com/odduse_/"><img src="https://cdn.svgporn.com/logos/instagram-icon.svg" alt="Instagram logo" width="13" height="13" /> Instagram</a>
- <a href="https://twitter.com/odduse_"><img src="https://cdn.svgporn.com/logos/twitter.svg" alt="Twitter logo" width="13" height="13" /> Twitter</a>
- <a href="https://www.facebook.com/odduse"><img src="https://cdn.svgporn.com/logos/facebook.svg" alt="Facebook logo" width="13" height="13" /> Facebook</a>
- <a href="https://www.linkedin.com/company/27092780/"><img src="https://cdn.svgporn.com/logos/linkedin.svg" alt="LinkedIn logo" width="13" height="13" /> LinkedIn</a>
- <a href="https://www.youtube.com/channel/UC4tKbCNIG-z4mNnc-gesF9Q"><img src="https://cdn.svgporn.com/logos/youtube.svg" alt="YouTube logo" width="13" height="13" /> YouTube</a>
- <a href="https://github.com/Odd-use"><img src="https://cdn.svgporn.com/logos/github-icon.svg" alt="Github logo" width="13" height="13" /> Github</a>
- <a href="mailto:info@odduse.com"><img src="https://cdn.svgporn.com/logos/google-gmail.svg" alt="eMail logo" width="13" height="13" /> eMail</a>

## Contributing

Please read through our [contributing guidelines](https://github.com/Odd-use/odd-gat/blob/main/CONTRIBUTING.md). Included are directions for opening issues, coding standards, and notes on development.

## Bugs, Feature requests, Questions & Need help

Have a bug, feature request, need help or just want to question? Please first read the [issue guidelines](https://github.com/Odd-use/odd-gat/blob/main/.github/CONTRIBUTING.md#using-the-issue-tracker) and search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/Odd-use/odd-gat/issues/new).

- [🐛 Report a bug](https://github.com/Odd-use/odd-gat/issues/new?template=BUG_REPORT.md)
- [🛠️ Feature request](https://github.com/Odd-use/odd-gat/issues/new?template=FEATURE_REQUEST.md)
- [💬 Ask a question](https://github.com/Odd-use/odd-gat/issues/new?template=QUESTION.md)

## Versioning

For transparency into my release cycle and in striving to maintain backward compatibility, odd-gat is maintained under the [Semantic-Release](https://semantic-release.gitbook.io/semantic-release/) & [Semantic Versioning guidelines](https://semver.org). Sometimes we screw up, but we adhere to those rules whenever possible.

See the Releases section of our GitHub project for [CHANGELOG](https://github.com/Odd-use/odd-gat/blob/main/CHANGELOG.md) for each release version of odd-gat projects.

## Creator

| Avatar                                         | Name        | Email                 | Website                                  |
| ---------------------------------------------- | ----------- | --------------------- | ---------------------------------------- |
| ![Jonas Bröms Avatar](docs/img/jonasbroms.png) | Jonas Bröms | jonasbroms@icloud.com | [jonasbroms.com](https://jonasbroms.com) |

## Copyright and license

This project is licensed under the terms of the MIT license.
For more information, [click here](https://github.com/Odd-use/odd-gat/blob/master/LICENSE).
