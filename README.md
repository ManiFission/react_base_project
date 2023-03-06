# react_base_project
Base application with required configurations for better development

## Core Structure
      ├── .storybook
      ├── public
      │   ├── favicon.ico
      │   ├── vite.svg
      ├── src
      │   ├── assets
      │   │   ├── **/*.svg
      │   ├── Components
      │   │   ├── LandingPage
      │   │   ├── User
      │   │   ├── NotFound
      │   ├── Stories
      │   │   ├── Header.tsx
      │   │   ├── Header.stories.tsx
      │   ├── utils
      │   │   ├── helper.ts
      │   │   ├── models.ts
      │   ├── Hooks
      │   │   ├── customHook.ts
      │   ├── Contexts
      │   │   ├── authContext.tsx
      │   ├── App.tsx
      │   ├── App.css
      │   ├── main.tsx
      │   ├── main.css
      │   ├── utils.css
      ├── node_modules
      ├── package.json
      ├── package-lock.json 
      ├── .eslintignore
      ├── .eslintrc.json
      ├── .huskyrc.json
      ├── .npmrc
      ├── .prettierrc.json
      ├── README.md
      ├── tsconfig.json
      ├── tsconfig.node.json
      ├── vite.config.ts
      └── .gitignore

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

Vite is an open-source, build tool for front-end web development created by Evan You, the creator of Vue.js. It is designed to provide fast and efficient development experience by optimizing the build and bundling process.

Vite is built on top of the modern web platform, leveraging native ES modules in the browser to eliminate the need for bundling during development. This allows for faster build times and hot module replacement, allowing developers to see changes in real-time without the need to rebuild and refresh the browser.

Vite supports multiple front-end frameworks such as Vue.js, React, Preact, and Svelte, and can be used to develop both client-side and server-side rendered applications. It also includes support for CSS pre-processors such as Sass, Less, and Stylus, as well as TypeScript and JavaScript.

One of the main advantages of Vite is its simplicity and ease of use. Developers can get started quickly with minimal configuration, and the tool offers an intuitive development experience with minimal boilerplate code.

Overall, Vite is a fast and efficient build tool that is well-suited for modern front-end development. Its simplicity and ease of use make it a popular choice among developers, particularly those working with Vue.js, React or other modern front-end frameworks.

## Eslint

ESLint is an open-source, pluggable linting utility for JavaScript. It is designed to help developers find and fix common programming errors, enforce coding conventions, and maintain consistent code style across large codebases. ESLint is highly configurable, and can be customized to suit the specific needs of a project or organization.

ESLint can be configured to check for a wide range of programming errors and style issues, such as undefined variables, unused variables, missing semicolons, unreachable code, incorrect indentation, and more. But with an .eslintrc file in place in your project, it sets up guardrails around the project to ensure each JavaScript file written adheres to the same standards as the others, regardless of who’s working on it. It also supports a variety of plugins and extensions that add additional functionality, such as compatibility with specific frameworks or libraries.

ESLint is great for the more specific, less generic code styles that you want your development team to adhere to. Unless you specifically set it up, ESLint won’t autofix or rewrite your code, but it will let you know in a straightforward way that there’s “rules” being broken.

## Husky

Husky is a Git tool that enables developers to set up Git hooks easily. Git hooks are scripts that run automatically whenever certain Git events occur, such as committing changes or pushing to a remote repository. Husky simplifies the process of setting up and managing Git hooks, making it easier for developers to enforce best practices and streamline their workflow.

Husky also includes a range of built-in Git hooks that can be used to enforce best practices and improve the quality of code. These include pre-commit hooks for running linting, code formatting, and unit tests, as well as pre-push hooks for running integration tests and other checks. 

## Lint-Staged

Lint-staged is a Git tool that enables developers to automatically run linters on files that are staged for commit. Linters are static analysis tools that check code for potential errors, bugs, and stylistic issues, helping to improve the quality and consistency of code. By running linters only on staged files, lint-staged can help to speed up the development process and reduce the number of errors that make it into production.

Lint-staged is typically used in conjunction with other Git tools such as Husky and Prettier to automate and streamline the development process. When combined with Husky, for example, lint-staged can be configured to run automatically before each commit, ensuring that only high-quality, error-free code is committed to the repository.

## Prettier

Prettier is an open-source code formatter that helps to maintain consistent code style across a codebase. It is designed to be easy to use and highly configurable, allowing developers to customize their formatting preferences to suit the needs of their project.

In a React project, Prettier is often used in combination with other tools such as ESLint and Git hooks to automate the process of formatting code and catching formatting errors. Prettier can be integrated into a React project using a variety of build tools and editors, including webpack, Babel, VS Code, and more.

Prettier works by analyzing the code in a project and automatically applying formatting rules to ensure that the code is formatted consistently. It can be configured to enforce a wide range of formatting options, such as indentation, line length, and whitespace, and can be set up to automatically format code on save or on commit.

## Storybook

React Storybook is an open-source tool for building and testing UI components in React. It provides a sandbox environment for developers to isolate and interact with components in isolation, without the need to set up a full application or navigate complex codebases.

React Storybook allows developers to create interactive documentation for their components, with a focus on modularity and reusability. It offers a visual testing environment where developers can experiment with different component variations, states, and interactions.

React Storybook works by providing a dedicated environment for each component, with a set of props and states that can be adjusted and previewed in real-time. This allows developers to see how their components will look and behave under different conditions, without having to switch between multiple contexts.

React Storybook is highly extensible and customizable, with support for addons that can be used to add functionality such as accessibility testing, component documentation, and more. It is widely used in the React community and is considered a best practice for developing and testing UI components.

Build Storybook: Build Storybook by running the following command in your project directory:

```bash
npm run storybook
```
This will start a Storybook server that you can access in your browser at http://localhost:6006.

