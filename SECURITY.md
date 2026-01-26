# Security Policy

This security policy applies to all repositories hosted under the [Guanyang](https://github.com/guanyang) GitHub account, unless a specific repository has its own overriding `SECURITY.md`.

## Reporting a Vulnerability

We take the security of our software seriously. If you believe you have found a security vulnerability in any of our projects, please report it to us as described below.

### ❌ Do NOT open a public GitHub Issue

**Please do NOT open a public specific GitHub Issue to report a security vulnerability.** Publicly disclosing a vulnerability can put the entire community at risk before a fix is available.

### ✅ How to Report

Please email a detailed report to **[guanyangsunlight@163.com]**.

In your email, please include:
*   The specific project/repository name.
*   Type of vulnerability (e.g., SQL Injection, Remote Code Execution, Prompt Injection).
*   Full steps to reproduce the vulnerability (proof-of-concept code is highly appreciated).
*   Any relevant logs or output.

### Response Timeline

*   **Acknowledgment**: We will make a best effort to acknowledge your email within **48 hours**.
*   **Assessment**: We will confirm the vulnerability and determine its severity within **1 week**.
*   **Fix**: We will aim to release a patch or workaround as soon as possible, depending on the complexity.

### Scope

This policy covers:
*   Security bugs in the core code.
*   Vulnerabilities in our default configurations.
*   Exposure of sensitive data (e.g., leaked API keys in the repo history).

This policy **does not** cover:
*   Vulnerabilities in third-party libraries we depend on (unless an upgrade is required on our end).
*   Issues related to user misconfiguration.
*   Attacks requiring physical access to the user's device.
*   SaaS infrastructure (if applicable) - please report those to the specific platform provider.

## Security Best Practices for Users

*   **API Keys**: Never commit your LLM API keys (OpenAI, Anthropic, etc.) or Database credentials to your forks or codebases. Use Environment Variables (`.env` files).
*   **Sandboxing**: For AI Agent projects that execute code (e.g., `antigravity-skills`), we strongly recommend running them in a sandboxed environment (Docker containers) to prevent unintended system modifications.

Thank you for helping keep our projects safe!
