# Contributing to Reiseplaner

Thank you for your interest in contributing to **Reiseplaner**! We welcome contributions from everyone.

This document provides guidelines for contributing to the project. Please read it carefully before submitting your contributions.

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md) (if available) or generally by respectful and inclusive behavior.

## How Can I Contribute?

### Reporting Bugs

If you find a bug, please open an issue on GitHub with the following information:

- A clear and descriptive title
- Steps to reproduce the issue
- Expected behavior
- Actual behavior
- Screenshots or error messages (if applicable)
- Your operating system and version
- The version of the tool you're using

### Suggesting Enhancements

We welcome feature requests and enhancement suggestions! Please open an issue with:

- A clear description of the proposed feature
- The problem it solves
- Any potential alternatives you've considered
- Examples or mockups (if applicable)

### Contributing Code

1. **Fork the repository** and create your feature branch from `main`
2. **Follow the coding style** used in the project (consistent with existing code)
3. **Write tests** for new functionality
4. **Ensure all tests pass** before submitting
5. **Commit your changes** with clear, descriptive commit messages
6. **Push to your fork** and submit a pull request

### Pull Request Guidelines

- Use a clear, descriptive title
- Provide a detailed description of the changes
- Reference any related issues
- Keep pull requests focused on a single feature or fix
- Ensure all commits are properly signed (if required)
- Update documentation if applicable

## Development Setup

### Prerequisites

- Rust (latest stable version)
- Git
- Cargo

### Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-org/reiseplaner.git
   cd reiseplaner
   ```

2. Install dependencies:
   ```bash
   cargo build
   ```

3. Run tests:
   ```bash
   cargo test
   ```

4. Run the application:
   ```bash
   cargo run
   ```

## Coding Standards

- Follow Rust's standard style conventions (rustfmt)
- Use meaningful variable and function names
- Add comments where code is non-obvious
- Keep functions small and focused
- Handle errors gracefully
- Write comprehensive tests

## Commit Message Format

We follow conventional commit messages:

```
type(scope): subject

body (optional)
footer (optional)
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`, etc.

Examples:
- `feat(packlist): add standard items per category`
- `fix(route): correct time zone handling`
- `docs: update README with installation instructions`

## Testing

All contributions should include appropriate tests:

- Unit tests for individual functions
- Integration tests for component interactions
- End-to-end tests for user flows

Run all tests before submitting:
```bash
cargo test
```

## Documentation

- Update documentation when adding new features
- Keep README.md up to date
- Add inline code comments where necessary
- Maintain consistent documentation style

## License

By contributing to this project, you agree that your contributions will be licensed under the same license as the project (MIT or Apache 2.0, as specified in the LICENSE file).

## Recognition

All meaningful contributions will be recognized. We appreciate your time and effort in making this project better!

## Need Help?

If you have questions about contributing, please:
- Check existing issues and discussions
- Open a new discussion for general questions
- Contact the maintainers directly if needed

---

Thank you for contributing to Reiseplaner! Your help makes this project better for everyone.
