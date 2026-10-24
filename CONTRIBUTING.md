# Contributing to PowerOS
> Copyright (C) 2026 QMX Corporation

Thank you for your interest in contributing to the PowerOS core repository. Because this system executes in a freestanding C architecture directly within Ring 0, all contributions must undergo extreme technical evaluation.

## Contribution Rules

### 1. Code Style Enforcement
- Every C file modification MUST pass local linting via the `.clang-format` matrix.
- Ensure all line breaks conform to Unix-style `LF` encoding as defined in `.editorconfig`.
- Do not commit trailing spaces or unnecessary blank separation lines.

### 2. Binary and Optimization Controls
- Keep implementation blocks lean. Avoid adding heavy abstractions or pseudo-C++ layouts inside the C core.
- All code vectors must be engineered to maintain minimal clock cycle counts and optimize instruction execution speeds.

### 3. Submission Protocol
- Fork the repository, apply your modifications on a clean branch, and submit a Pull Request.
- Describe exactly what your patch fixes or optimizes. The founder will review and determine if the patch undergoes merge or cancellation.

**Happy Coding!**
