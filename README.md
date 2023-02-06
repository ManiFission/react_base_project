# react_base_project
Base application with required configurations for better development

## Prerequisites

### Install Node JS >= 14 (comes with npm 6+)
Refer to https://nodejs.org/en/ to install nodejs

## Cloning and Running the Application in local

Clone the project into your local machine

```bash
git clone https://github.com/ManiFission/react_base_project.git
```

Switch to directory 

```bash
cd react_base_project
```

Install all the npm packages. Go into the project folder and type the following command to install all npm packages and run the application

```bash
npm install && npm run dev
```

## What is Vite?

Vite is a build tool that aims to bridge the gap between current and next-generation web development. It focuses on providing a faster and more performant experience for developers and modern web projects.

Vite is built on top of esbuild, a JavaScript bundler written in Go, which bundles dependencies 10-100 times faster than JavaScript-based bundlers.

## Eslint

ESLint allow developers to discover problems with their JavaScript code without executing it.

ESLint is great for the more specific, less generic code styles that you want your development team to adhere to. Unless you specifically set it up, ESLint won’t autofix or rewrite your code, but it will let you know in a straightforward way that there’s “rules” being broken.

Whether those rules include commented out code, unused variables or missing prop-types is up to you and your team, but with an .eslintrc file in place in your project, it sets up guardrails around the project to ensure each JavaScript file written adheres to the same standards as the others, regardless of who’s working on it.

## Husky

Husky is a tool that allows us to work with Git hooks. Git hooks are scripts that you can set up to run at certain events in the Git lifecycle. In our case, we will be using Husky to run ESlint and Prettier as our pre-commit hook so that no one will be able to commit when their code doesn't follow our rules.

## Lint-Staged

Lint Staged is used to run linter to staged git files and prevent from committing the buggy code.
