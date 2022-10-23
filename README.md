# `danoc/pnpm-setup-composite-action`

This composite GitHub Action checks out a codebase, sets up Node, pnpm, installs dependencies, and manages a cache.

## Requirements

1. A `.node-version` file in the root of your repository
2. A `"packageManager": "pnpm@<version>"` field in the root `package.json` file

These requirements are opinionated because this was created for [@danoc](https://github.com/danoc) to use in personal projects.

## Publishing a new version

1. Create a new Git tag with `git tag -a -m "<message>" v<version>`.
2. Push the tag to GitHub with `git push --follow-tags`.
