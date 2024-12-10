# Web todo template

## Setup

1. This project is set up with the [pnpm](https://pnpm.io/installation#using-npm) package manager, you need to install it.
2. Fork and clone this repository.
3. From your CLI, move to the project repository with `cd`.
4. Install the dependencies with `pnpm i`.

That's all ! You are ready to go.

## How to develop with this template ?

This template is based on [vite](https://vite.dev/), with some aditionnal tooling, here are the most important things :

- Use `pnpm dev` command to launch the development server on [localhost:5173](http://localhost:5173/).
- Use `pnpm check-types` to launch the [TypeScript](https://www.typescriptlang.org/) type checker, this will verify the project type correctness.
- Use `pnpm format` to format all project files correctly.
- Use `pnpm lint` to run the [biome](https://biomejs.dev/) linter, and catch some errors statically.

These commands allow you to create good quality commits. Don't forget to lint and format before your commits.

## Continuous integration

This repo includes two [GitHub actions](https://docs.github.com/en/actions) :

- One to automatically deploy the project to GitHub pages. This workflow executes on each commits in main branch.
- One to check the code formatting and linting, this one executes on pull requests.