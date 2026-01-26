# Contributing to Guanyang's Projects

First off, thank you for considering contributing to my open source projects! It's people like you that make the open source community such an amazing place to learn, inspire, and create.

Since this is a default contributing guide for all my repositories (unless a specific project has its own), the following guidelines are general but important.

## 🛠 How Can You Contribute?

### 1. Reporting Bugs
This section guides you through submitting a bug report. Following these guidelines helps maintainers and the community understand your report, reproduce the behavior, and find related reports.

- **Check if the bug has already been reported**.
- **Use the template**. If the repository has an Issue Template, please follow it.
- **Describe the bug**. Explain the behavior you expected and what actually happened.
- **Provide reproduction steps**. A small code snippet or a repo that reproduces the issue is incredibly helpful.

### 2. Suggesting Enhancements
This section guides you through submitting an enhancement suggestion, including completely new features and minor improvements to existing functionality.

- **Use a clear and descriptive title** for the issue to identify the suggestion.
- **Provide a step-by-step description of the suggested enhancement** in as much detail as possible.
- **Explain why this enhancement would be useful** to most users.

### 3. Pull Requests
The process described here has several goals:
- Maintain the quality of the code.
- Fix problems that are important to users.
- Engage the community in working toward the best possible solution.

**Please follow these steps:**

1.  **Fork the repository** and create your branch from `main` or `master`.
2.  **Clone the repository** to your local machine.
3.  **Create a new branch**: `git checkout -b fix/your-fix-name` or `git checkout -b feat/your-feature-name`.
4.  **Make your changes**. Ensure you follow the coding style (see below).
5.  **Test your changes**. Run existing tests and add new ones if necessary.
6.  **Commit your changes** using descriptive commit messages.
7.  **Push to your fork** and submit a Pull Request.

## 🎨 Coding Styleguides

Since I work primarily with **Java/Spring** and **Python/AI**, please adhere to the standard conventions for these languages.

### Java (Spring Boot Projects)
- **Style**: Follow standard [Google Java Style](https://google.github.io/styleguide/javaguide.html) or [Spring Framework Code Style](https://github.com/spring-projects/spring-framework/wiki/Code-Style).
- **Naming**: Use `CamelCase` for classes and methods, `UPPER_CASE` for constants.
- **Comments**: Javadoc is required for public methods and classes.
- **Lombok**: If the project uses Lombok, please utilize it to keep code clean.

### Python (AI & Agent Projects)
- **Style**: Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/).
- **Typing**: Type hints are strongly encouraged for function arguments and return types.
- **Docstrings**: Use Google-style or NumPy-style docstrings.
- **Formatter**: Projects often use `black` or `isort`. Please run them before committing.

### General
- **Clean Code**: Keep functions small and focused.
- **No commented-out code**: Remove it instead of commenting it out.
- **Git Commit Messages**: Use the [Conventional Commits](https://www.conventionalcommits.org/) format if possible (e.g., `feat: add new skill definition`, `fix: resolve NPE in user service`).

## 🤝 Code of Conduct

By participating in this project, you are expected to uphold a safe, welcoming, and inclusive environment. Please be professional and respectful in all communications.

## ❓ Questions?

If you have questions, feel free to start a Discussion or open an Issue labeled "question".

---
*Thanks again for your contribution!*
*— Guanyang*
