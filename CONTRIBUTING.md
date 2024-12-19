# Contributing to Apple Notifier MCP Server

First off, thank you for considering contributing to the Apple Notifier MCP Server! It's people like you that make it a great tool for everyone.

## Code of Conduct

This project and everyone participating in it is governed by our code of conduct. By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the existing issues as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

* Use a clear and descriptive title
* Describe the exact steps which reproduce the problem
* Provide specific examples to demonstrate the steps
* Describe the behavior you observed after following the steps
* Explain which behavior you expected to see instead and why
* Include details about your configuration and environment:
  * Which version of Node.js are you using?
  * Which version of macOS are you using?
  * Which MCP client are you using (Claude Desktop, Cline, etc.)?

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

* A clear and descriptive title
* A detailed description of the proposed functionality
* Explain why this enhancement would be useful
* List any alternative solutions or features you've considered

### Pull Requests

* Fill in the required template
* Do not include issue numbers in the PR title
* Include screenshots and animated GIFs in your pull request whenever possible
* Follow the TypeScript styleguide
* Include thoughtfully-worded, well-structured tests (when we implement testing)
* Document new code
* End all files with a newline

## Development Process

1. Fork the repo and create your branch from `main`
2. Run `npm install` to install dependencies
3. Make your changes
4. Test your changes thoroughly
5. Ensure the code lints successfully
6. Create a Pull Request

### Styleguides

#### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line

#### TypeScript Styleguide

* Use 2 spaces for indentation
* Prefer `const` over `let`
* Use meaningful variable names
* Add types for parameters and return values
* Use async/await over raw promises
* Document public methods with JSDoc comments

## Project Structure

```
apple-notifier-mcp/
├── src/                    # Source files
│   ├── index.ts           # Main MCP server implementation
│   ├── notifier.ts        # Core notification functionality
│   └── types.ts           # Type definitions
├── build/                 # Compiled files (git ignored)
├── package.json           # Project metadata and dependencies
└── tsconfig.json          # TypeScript configuration
```

## Setting Up Development Environment

1. Ensure you have Node.js >= 18 installed
2. Clone your fork of the repository
3. Run `npm install` to install dependencies
4. Run `npm run dev` to start in development mode
5. Make your changes
6. Test thoroughly
7. Submit a PR

## Questions?

Feel free to open an issue with your question. We'll do our best to answer promptly.