# APM — Alca Package Manager & Registry

[English](README.md) | [Русский](README_RU.md)

**APM** is the official package manager, registry server, and package index for the [Alca Programming Language](https://github.com/alca-lang/alca).

## Features
- **Deterministic Builds**: Strict SemVer resolution and lockfiles (`alca.lock`).
- **Zero-Toolchain Compilation**: Automatic multi-platform native artifact builds.
- **Embedded Web Registry**: PyPI-inspired package index with SVG vector icons and search.
- **Documentation Engine**: Interactive documentation in Arch Linux Wiki + Python Docs style.
- **Security**: SHA-256 integrity verification, token-based publishing, and Zip-Slip protection.

## Installation
```powershell
# Windows PowerShell
irm https://raw.githubusercontent.com/alca-lang/apm/master/scripts/install.ps1 | iex
```

```bash
# Linux / macOS
curl -fsSL https://raw.githubusercontent.com/alca-lang/apm/master/scripts/install.sh | bash
```

## Quick Start
```bash
# Initialize a new package
apm init my-lib

# Install dependencies
apm add mathutils

# Publish to the registry
apm publish
```

## License
Apache-2.0
