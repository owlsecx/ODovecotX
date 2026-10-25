# 🦉 ODovecotX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-ONetwork-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **ODovecotX** — Dovecot IMAP / POP3 Configuration Auditor

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

ODovecotX — Dovecot IMAP / POP3 Configuration Auditor. It provides stdlib Dovecot parser — sections, !include globs, <file values, $vars, `doveconf -n` exports; Auth, passdb / userdb (hashes never printed), SQL / LDAP ext, TLS, listeners, services, sieve. Built-in demo/self-test paths and severity gates help validate detections without touching production when those flags are used.

---

## ✨ Features

- Stdlib Dovecot parser — sections, !include globs, <file values, $vars, `doveconf -n` exports
- Auth, passdb / userdb (hashes never printed), SQL / LDAP ext, TLS, listeners, services, sieve
- Secrets masked; CWE + MITRE ATT&CK per rule
- Export TXT / Markdown / JSON / CSV / SARIF 2.1.0
- Self-test --demo, CI gates --fail-on / --min-severity

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./ODovecotX                                     # interactive menu
./ODovecotX --scan -r /path/to/root
./ODovecotX --demo
./ODovecotX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
