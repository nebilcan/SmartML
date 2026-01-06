# Security Policy

## Supported Versions

SmartEco is an open-source research Ecosystem.

Security fixes are applied **only to the latest released version**.  
Older versions are **not actively maintained**.

| Version | Supported |
|--------|-----------|
| Latest |  Yes |
| Older |  No |

---

## Reporting a Vulnerability

If you discover a **security vulnerability**, please report it responsibly.

### How to Report

- **Do not** open a public GitHub issue
- **Do not** disclose details publicly before a fix

Instead, report via one of the following:

- GitHub Security Advisories (preferred)
- Direct message to the project maintainer via GitHub

When reporting, please include:
- A clear description of the issue
- Steps to reproduce (if applicable)
- Affected component(s)
- Potential impact

---

## Scope of Security Considerations

SmartEco and SmartML are:
- **CPU-first**
- **Offline**
- **Non-networked**
- **Non-commercial**
- **Benchmarking and evaluation tools**

As such, the primary security scope includes:
- Unsafe file handling
- Arbitrary code execution via inputs
- Dependency-related vulnerabilities
- Serialization or deserialization risks

The following are **out of scope**:
- Model accuracy issues
- Benchmark performance differences
- Research model instability
- Experimental or optional third-party libraries

---

## Dependency Policy

SmartEco relies on widely-used scientific Python libraries.

- Optional dependencies are **guarded and isolated**
- Missing or incompatible libraries are **never imported implicitly**
- Models are exposed **only if available at runtime**

Users are responsible for:
- Keeping dependencies up to date
- Reviewing third-party licenses and security advisories

---

## Disclosure Policy

- Valid security issues will be acknowledged promptly
- Fixes will be released as soon as reasonably possible
- No guaranteed response time, but good-faith effort is made

SmartEco is maintained as an **open-source research project** without commercial SLA.

---

## Thank You

Responsible disclosure helps keep the ecosystem safe and trustworthy.

Thank you for helping improve SmartEco.
