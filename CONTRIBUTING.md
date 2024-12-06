# Contributing to SimpleWImage

Thank you for considering contributing to **SimpleWImage**! We welcome contributions from everyone, and we encourage you to improve and extend the project. Before you contribute, please read and follow the guidelines below to ensure a smooth collaboration.

## Table of Contents

- [How to Contribute](#how-to-contribute)
  - [Reporting Issues](#reporting-issues)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Creating Pull Requests](#creating-pull-requests)
- [Code of Conduct](#code-of-conduct)
- [Development Guidelines](#development-guidelines)
- [Testing](#testing)
- [Licensing](#licensing)

## How to Contribute

There are several ways you can contribute to **SimpleWImage**:

### Reporting Issues

If you find a bug or have encountered an issue, please check the [existing issues](https://github.com/yourusername/SimpleWImage/issues) to see if it's already been reported. If not, you can create a new issue. When reporting an issue, please include:

- A clear description of the problem.
- Steps to reproduce the issue.
- The environment in which the issue occurs (e.g., operating system, version of Python, etc.).
- Screenshots or error messages (if applicable).

### Suggesting Enhancements

If you have an idea for a feature enhancement or an improvement to **SimpleWImage**, please open a new issue and clearly describe the suggestion. You can also comment on existing issues to provide additional input or vote for a feature you would like to see.

### Creating Pull Requests

We welcome contributions in the form of **pull requests (PRs)**. Before submitting a PR, please make sure that:

- You have forked the repository and created a branch for your changes (e.g., `feature/your-feature` or `bugfix/issue-number`).
- Your changes are based on the latest `main` branch.
- Your code follows the [PEP 8](https://www.python.org/dev/peps/pep-0008/) style guide and is properly formatted. Use `black` for code formatting (or the equivalent style used by the project).
- You have written tests (if applicable) for your changes.
- Your PR includes a description of the problem, the solution, and any relevant context.

To submit your PR, follow these steps:

1. Fork the repository and clone it to your local machine.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with a clear and concise commit message.
4. Push your changes to your forked repository.
5. Open a pull request to the `main` branch of the original repository.

## Code of Conduct

By participating in this project, you agree to abide by the [Code of Conduct](CODE_OF_CONDUCT.md). This document outlines our expectations for community behavior, as well as how to report violations.

We strive to create a welcoming and inclusive community for everyone, regardless of background or experience.

## Development Guidelines

To maintain the quality and consistency of the project, we ask that contributors follow these development guidelines:

### Coding Standards

- **Python version**: This project is compatible with Python 3.6 and above.
- **Code Style**: Follow the [PEP 8](https://www.python.org/dev/peps/pep-0008/) style guide for Python. Use a linter like `pylint` or `flake8` to ensure your code meets these standards.
- **Indentation**: Use 4 spaces for indentation. Do not use tabs.
- **Docstrings**: Write clear and concise docstrings for all functions and classes. Follow the [PEP 257](https://www.python.org/dev/peps/pep-0257/) conventions.
- **Function and Variable Names**: Use descriptive names for functions and variables, following the `snake_case` convention for variables and function names, and `CamelCase` for class names.
- **Comments**: Include comments where necessary, especially for complex or non-obvious code.

### Commit Messages

- Write clear, concise commit messages in the present tense (e.g., "Fix bug in image renaming feature").
- Use the following format for the commit message:
<type>(<scope>): <message>

<optional body explaining the change> ```
Example:

scss
Copiar código
fix(renaming): resolve issue with invalid filenames during renaming
The <type> should be one of:

feat: A new feature.
fix: A bug fix.
docs: Documentation changes.
style: Code style improvements (e.g., formatting, spacing).
refactor: Code refactoring (without changing functionality).
test: Adding or modifying tests.
chore: Miscellaneous changes (e.g., build tools, dependencies).
Testing
Please ensure your changes are properly tested. If you are adding new features or fixing bugs, create tests that verify your changes. SimpleWImage uses unittest as the testing framework, but feel free to use any other testing tools you prefer.

Running Tests
To run the tests:

Install the project dependencies, including testing tools:
bash
Copiar código
pip install -r requirements.txt
Run the tests:
bash
Copiar código
python -m unittest discover
Ensure that all tests pass before submitting your pull request.

Licensing
By contributing to SimpleWImage, you agree that your contributions will be licensed under the MIT License. Please see the LICENSE file for more details.

Thank you for contributing to SimpleWImage! Your contributions help make this project better for everyone. If you have any questions or need further assistance, feel free to reach out.
