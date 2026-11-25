# ayo-recon 🛡️

A lightweight, zero-dependency **Python 3 CLI security posture inspector** that audits domain DNS resolution, TLS/SSL certificate health, server banner disclosures, and **OWASP-recommended HTTP security headers**.

> **Ethical Use Disclaimer:** This tool performs non-intrusive passive DNS, TLS handshake, and HTTP response header inspection. Only scan domains and web applications you own or have explicit authorization to assess.

---

### ✨ Features
* **DNS Resolution Check:** Resolves IPv4/IPv6 host records and measures response latency.
* **TLS / X.509 Certificate Inspection:** Verifies active TLS protocol version (`TLSv1.2` / `TLSv1.3`), cipher suite, issuing Certificate Authority, and days remaining until certificate expiration.
* **OWASP HTTP Security Headers Audit:** Evaluates key browser-hardening headers (`Strict-Transport-Security`, `Content-Security-Policy`, `X-Content-Type-Options`, `X-Frame-Options` / CSP `frame-ancestors`, `Referrer-Policy`, and `Permissions-Policy`), assigns a `0–100` posture score (`A`–`F`), and outputs actionable remediation steps.
* **Technology Banner Disclosure Detection:** Flags exposed `Server` or `X-Powered-By` headers that leak backend stack details.
* **Zero External Dependencies:** Built 100% with Python's standard library (`argparse`, `socket`, `ssl`, `urllib`, `json`) so it runs cleanly on Linux, Windows, macOS, **Termux**, and **Pydroid 3**.

---

### 🚀 Quick Start

#### 1. Clone the Repository
```bash
git clone [https://github.com/saidujoseph260-bot/ayo-recon.git](https://github.com/saidujoseph260-bot/ayo-recon.git)
cd ayo-recon
