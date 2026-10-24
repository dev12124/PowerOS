# Security Policy: PowerOS Hardcore Buffer Protection
> Copyright (C) 2026 QMX Corporation

As a freestanding, bare-metal operating system executing in C directly within CPU Ring 0, memory safety is paramount to prevent kernel crashes and unauthorized execution loops.

## Reporting a Vulnerability
If you discover a memory leak, buffer overflow, or an architecture exploit within the PowerOS core, please follow these guidelines:

1. **Do Not Open a Public Issue:** To protect running systems from exploits, do not disclose vulnerabilities in the public issue tracker.
2. **Private Notification:** Submit a detailed audit report directly to the lead technical coordinator (**João Guilherme da Silva Freitas Lima**) via the official QMX organization channels or discord workspace.
3. **Assessment:** The QMX Corporation pipeline will review the code vector, compute clock cycle impacts, and push a predictive patch to the repository.

Thanks for keeping the Temple secure!
