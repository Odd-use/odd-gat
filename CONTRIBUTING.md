# Contributing

- [Submitting changes](#submitting-changes)
- [Issues and labels](#issues-and-labels)
- [Commit with Terminal commands](commit-with-terminal-commands)
- [Commit with Commitizen](#commit-with-commitizen)

## Submitting changes

If this is the first time you are contributing to an Open-Source project we would really appreciate if you would read the [Open-Source.guide](https://opensource.guide/) before committing.

## Issues and labels

| Type             | Git Label                                                      | Explanation                                                    |
| ---------------- | -------------------------------------------------------------- | -------------------------------------------------------------- |
| bug              | ![bug label](docs/img/label-bug.png)                           | A bug fix                                                      |
| feature          | ![feature label](docs/img/label-feature.png)                   | A new feature                                                  |
| documentation    | ![documentation label](docs/img/label-documentation.png)       | Documentation improvements                                     |
| style            | ![style label](docs/img/label-style.png)                       | Changes made white-space, formatting, missing semi-colons, etc |
| refactor         | ![refactor label](docs/img/label-refactor.png)                 | A code change that neither fixes a bug nor adds a feature      |
| performance      | ![performance label](docs/img/label-performance.png)           | Performance improvements                                       |
| test             | ![test label](docs/img/label-test.png)                         | Add missing tests                                              |
| chore            | ![chore label](docs/img/label-chore.png)                       | Changes the build process                                      |
| released         | ![released label](docs/img/label-released.png)                 | Used by Semantic-Release-Bot                                   |
| duplicate        | ![duplicate label](docs/img/label-duplicate.png)               | This issue or pull request already exists                      |
| wontfix          | ![won't fix label](docs/img/label-wontfix.png)                 | This will not be worked on                                     |
| helpwanted       | ![help wanted label](docs/img/label-help-wanted.png)           | Extra attention is needed                                      |
| question         | ![question label](docs/img/label-question.png)                 | Further information is requested                               |
| good first issue | ![good first issue label](docs/img/label-good-first-issue.png) | Good for newcomers                                             |

## Commit with Terminal commands

Our bug tracker utilizes several labels to help organize and identify issues. Here's what they represent and how we use them:

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

```sh
$ git commit -m "feat: A brief summary of the commit"
```

| Type                | Explanation                                                    | Semver (eg. 1.5.2) | Git Message Example                                    |
| ------------------- | -------------------------------------------------------------- | ------------------ | ------------------------------------------------------ |
| **fix**             | A bug fix                                                      | x.x.**1**          | **fix:** _update package.json_                         |
| **feat**            | A new feature                                                  | x.**1**.x          | **feat:** _add new eslint to package.json_             |
| **BREAKING CHANGE** | A major change                                                 | **1**.x.x          | **BREAKING CHANGE:** _upgrade to strapi 3 & gatsby 3_  |
| **docs**            | Documentation improvements                                     |                    | **docs:** _update README.md_                           |
| **style**           | Changes made white-space, formatting, missing semi-colons, etc |                    | **style:** _add styles in breadcrumb component_        |
| **refactor**        | A code change that neither fixes a bug nor adds a feature      |                    | **refactor:** _fixed better intendation in index.html_ |
| **perf**            | Performance improvements                                       |                    | **perf:** _add tree-shaking to webpack_                |
| **test**            | Add missing tests                                              |                    | **test:** _add test to .travis.yml_                    |
| **chore**           | Changes the build process                                      |                    | **chore:** _update .travis.yml & netlify.toml_         |

## Commit with Commitizen

```sh
$ cz
```

## Git branches

| Name               | Fixed name | Run Test            | Description                                       |
| ------------------ | ---------- | ------------------- | ------------------------------------------------- |
| **Main**           | ❎         | 👍 Semantic Release | Public, Semantic Release bot & publish on Netlify |
| **[Pull request]** |            | 👍 Lighthouse       | Pull request made from Next to Main               |
| **Next**           | ❎         |                     | Beta/Stage                                        |
| **"Develop"**      |            |                     |                                                   |

```text
◎ <-- Main
┃
┠─[Pull request]─╮
┃                ⊙ <-- Next
┃                │
┃                ├┄┄┄┄┄╮
┃                │     ┆
┃                │     ◌ <-- "Develop"
┃                │     ┆
┃                │     ┆
●                ○     ◌
```

## Releases

See the Releases section of our GitHub project for [CHANGELOG](https://github.com/odduse/odd-gat/blob/main/CHANGELOG.md) for each release version of MaterialUI projects.

## Checking coding style

Run `npm i` & `npm run test` before committing to ensure your changes follow our coding standards.
