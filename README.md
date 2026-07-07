# Security Research

Public vulnerability research — CVE writeups, root-cause analysis, and proof-of-concept code for vulnerabilities I've found and responsibly disclosed in open-source software.

---

## Findings

| CVE | Target | Severity | Type | Writeup |
|-----|--------|----------|------|---------|
| [CVE-2026-55480](https://github.com/OpenPrinting/cups/security/advisories/GHSA-jj94-x3qh-ffp9) | OpenPrinting CUPS ≤ 2.4.19 | Medium (5.7) | Symlink TOCTOU in `copy_model()` → arbitrary root file write (`lp` → root) | [writeup](CVEs/CVE-2026-55480-cups-copy-model-toctou/writeup.md) |
| [CVE-2026-55467](https://github.com/OpenPrinting/cups/security/advisories/GHSA-69qc-prxg-h2c7) | OpenPrinting CUPS ≤ 2.4.19 | Low (2.5) | Fax option path bypasses CVE-2026-34980 control-char sanitizer (incomplete fix) | [writeup](CVEs/CVE-2026-55467-cups-fax-sanitizer-bypass/writeup.md) |
| CVE-2026-XXXX *(pending)* | accountsservice / systemd-homed | Medium (6.1) | Arbitrary root file read via `SetIconFile` homed path → local privilege escalation | [writeup](CVEs/CVE-2026-XXXX-accountsservice-homed-seticonfile/writeup.md) |

---

## Responsible Disclosure

All vulnerabilities in this repository were reported to the respective maintainers before publication. I follow a responsible disclosure approach — notifying vendors, allowing time for a fix, and publishing only after a patch is available.

If you believe you've found a security issue in an open-source project, consider reporting it directly to the maintainers via their security policy or a private advisory.

---

## About

Cybersecurity analyst with nearly four years of experience across defensive and offensive security. Currently focused on vulnerability research &mdash; root causes, OS internals, and application-layer flaws.

&rarr; [Portfolio](https://thureinoo.github.io) &middot; [GitHub](https://github.com/ThureinOo)
