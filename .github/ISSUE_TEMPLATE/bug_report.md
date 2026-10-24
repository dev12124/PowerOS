---
name: "🐛 Bug Report (Hardware & Compilation Crash)"
about: Report low-level execution errors, Clang build breaks, or kernel runtime crashes.
title: "[BUG]: "
labels: bug, freestanding-core
assignees: dev12124
---

## 💻 Hardware Environment Specification
- **Host Operating System:** (e.g., Windows 11, Ubuntu 24.04, Android Termux)
- **Processor / Architecture:** (e.g., Intel Tiger Lake x86_64, AMD Ryzen)
- **Compiler Version:** (Must be Clang v19.x or higher)
---

## 🚨 Description of the Crash / Bug
Provide a clear and concise description of what the low-level failure is and where the execution loop hangs.

### Reproduction Steps
1. Configure environment flags according to `Kconfig`.
2. Run the compilation pipeline command: `[Insert command here]`
3. Observe the compiler rejection or memory fault at address: `[Insert address or crash log]`

---

## 📊 Compilation Logs & Console Outputs
Paste the raw text terminal output containing the error messages below:

```text
[Paste terminal/Clang crash logs here]
```

---
*By submitting this bug report, you confirm that your local repository is 100% compliant with the official `.editorconfig` and `.clang-format` guidelines.*
