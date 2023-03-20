---
title: Git PreCommit Demo Project with Prettier & MarkdownLint
creation date: 2023-03-20-Monday
modification date: 2023-03-20-Monday 5:50pm
---

## About

This repo is a demo project for the setup of a Git [pre-commit hook](https://pre-commit.com/) with
[Prettier](https://prettier.io/docs/en/precommit.html) and MarkdownLint
([markdownlint-cli2](https://github.com/DavidAnson/markdownlint-cli2#pre-commit)).

### Motivation

I have been using [Obsidian](https://obsidian.md/)/VSCode for a lot of note taking/documentation
lately. I've been using git to back up everything.

I wanted to have a pre-commit hook that would run Prettier and MarkdownLint on my markdown files
before I commit them to git. I also wanted to have some practice with setting up a pre-commit hooks.

I spent forever trying to get everything to work as intended. I'd like to never do that ever again,
hence this template.

<a name="readme-top"></a>

## Dependencies

- [Prettier](https://prettier.io)
- [markdownlint](https://github.com/DavidAnson/markdownlint)
- [markdownlint-cli2](https://github.com/DavidAnson/markdownlint-cli2)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

After Cloning the repo, you'll need to install the dependencies.

```sh
pnpm install
```

Then you'll need to install the pre-commit hook.

```sh
pre-commit install
```

Now you're ready to go!
