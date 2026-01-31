# 🚀 PyEnvManager
**Docker Desktop for Python environments.**  
A cross-platform desktop app (Windows + macOS) for discovering, creating, securing, and managing Python environments — fast, visual, and safe.

📌 **Website:** https://pyenvmanager.com  
📦 **Releases:** https://pyenvmanager.com/releases.html  
🐛 **Issues:** https://github.com/Pyenvmanager/pyenvmanager-releases/issues  

---

## ⭐ What PyEnvManager Does
PyEnvManager is a **Python environment management and security platform** that discovers Python installations across your system — including the hidden ones.

### 🔍 Universal Discovery (Rust-Powered)
Automatically detects **all** Python environments with zero performance impact:

- **System Python** — Including hidden `/usr/local/bin/python` installations
- **venv** — Standard virtual environments (with creation support)
- **Conda / Mamba / Micromamba** — Data science environments
- **Poetry / Pipenv** — Modern dependency managers
- **UV** — Fast Python package installer
- **Shadow Binaries** — Hidden or orphaned Python installations
- **Full System Deep Scans** — High-performance Rust scanner finds everything

### 🛡️ Shift-Left Security
Enterprise-grade security features that catch issues **before** code commit:

- 🔍 **Vulnerability Scanning** — OSV database integration for real-time CVE detection
- 🛡️ **Accurate Severity Classification** — Proper CRITICAL → LOW mapping
- 📦 **Per-Environment Vulnerability Summaries** — Know your risk instantly
- 📜 **License Detection** — Catch GPL/AGPL violations before they reach production
- 📄 **SBOM Generation** — Compliance-ready reports in seconds
- 📊 **Self-Audit Reports** — Developers can prove they're clean without IT intervention
- 🔎 **Multi-Phase Scanning** — Discovery → Inventory → CVE Scan → SBOM → Report

All in a fast, modern UI built for developers, data scientists, and DevOps teams.

---

## 🔥 Latest Version: **v0.5.6** (Jan 31, 2026)

### 🐛 Git-Based Project Grouping - Fixed
- ✅ Environments now properly group by Git repository **immediately on launch**  
- ✅ No more manual refresh required for project-based organization  
- ✅ Git context persisted in cache for consistent grouping across sessions

### ⚡ Cache Persistence Enhancement
- ✅ Git repository metadata now saved in environment caches  
- ✅ Faster startup times with accurate project grouping from cached data  
- ✅ Deep scan cache includes full Git context for reliable organization

### 🎯 What This Means
- **Instant organization** — See your projects grouped correctly from the moment you open the app  
- **Consistent experience** — Grouping persists across restarts without re-scanning  
- **Better performance** — Reduced Git operations during startup

> **Full changelog:** [release-notes-v0.5.6.md](./release-notes-v0.5.6.md)

---

## 🌟 Recent Highlights

### v0.5.5 (Jan 4, 2026)
- 🧹 **Cache Cleanup Fix** — Deleted environments now properly removed from all cache files
- 🚀 **License Scanner Optimization** — Batch processing for faster package scans
- 🔧 **Version Management** — Centralized version handling across codebase

### v0.5.4 (Dec 15, 2025)
- 🛡️ **Vulnerability Classification Fix** — MODERATE severity CVEs now correctly classified (not HIGH)
- 📂 **Open Directory Buttons** — Quick access to environment folders and scan results
- 🐍 **venv Creation Fix** — Resolved "command not recognized" error with Python path resolution
- 🏢 **Enterprise Module** — Modular architecture for enterprise features

### v0.5.2 (Nov 2025)
- 🐍 **venv Support** — Create and manage standard Python virtual environments
- 🆕 **Python 3.13 Support** — Latest Python version support for Mamba environments
- 🔍 **Auto-Detection** — Automatically finds Python installations on your system

> See [FEATURES_CHANGELOG.md](./FEATURES_CHANGELOG.md) for complete version history

---

## 🔐 Security & Deep Scanning

### 🔍 Multi-Phase System Scan
- Environment discovery  
- Package inventory  
- Vulnerability scanning (OSV)  
- SBOM generation  
- Professional HTML reports  
- Scan history & deletion

### 🛡️ CVE Insights (Pro)
- Accurate severity mapping (CRITICAL → LOW)  
- Vulnerability grouping per environment  
- Executive summaries and detailed breakdowns  
- Fixed MODERATE severity classification in v0.5.4

---

## 🛠️ Core Features

### 🚀 Developer Velocity
- ⚡ **One-Click Activation** — Instantly launch a terminal with any environment pre-activated
  - *Solves "activation fatigue" and path configuration issues*
- 🔍 **Universal Discovery** — Rust-powered scanner finds Python installations system-wide
  - *See what traditional tools miss — including shadow binaries*
- 📂 **Git-Based Project Grouping** — Automatic organization by repository
  - *Zero configuration, instant project organization*
- 🎨 **Visual Environment Management** — Color-coded types, disk usage charts
  - *Know what's where, instantly*

### 🔬 Deep Inspection & Analysis
- 📦 **Complete Package Inventory** — Every package, version, and dependency
- 📜 **License Detection** — MIT, GPL, Apache, BSD — know before you commit
  - *Catch the bad license before it reaches production*
- 🔍 **CVE Vulnerability Scanning** — Real-time security analysis using OSV database
  - *Shift-left security: find vulnerabilities on the laptop, not in prod*
- 🔄 **Environment Diff** — Compare two environments side-by-side (Coming Soon)
  - *Instant drift detection: solve "works on my machine" problems*

### ⚙️ Lifecycle Management
- ✨ **Create Environments** — venv, Conda, Mamba, Micromamba support
  - *Standardized workflow across the entire team*
- 🧬 **Clone Environments** — Duplicate working configurations instantly
- 🧹 **Secure Deletion** — Clean removal from all caches and disk
- 📦 **Package Management** — Install, upgrade, remove packages from the UI
- 🗂️ **Environment Templates** — ML, SciPy, Web stacks (Pro)

### 🧪 Data Science Native
- 📒 **One-Click Jupyter Launch** — Open notebooks in the correct environment
  - *Built for the workflow of data scientists and ML engineers*
- 🐍 **Python 3.13 Support** — Latest Python versions
- 📊 **Package Visualization** — Understand your dependency tree

### 📄 Reporting & Compliance
- 📄 **One-Click SBOM Export** — HTML/JSON format for audits
  - *Compliance-ready in seconds*
- 📊 **Self-Audit Reports** — Prove you're clean without IT intervention
- 📂 **Scan History** — Track environment changes over time
- 📂 **Open Directory** — Quick access to environment folders and scan results

---

## 🧩 Supported Environments

| Manager       | Detection | Creation      | Package View | Deletion | Open Directory |
|---------------|-----------|---------------|--------------|----------|----------------|
| venv          | ✅        | ✅            | ✅           | ✅       | ✅             |
| Conda         | ✅        | ⚪            | ✅           | ✅       | ✅             |
| Mamba         | ✅        | ✅            | ✅           | ✅       | ✅             |
| Micromamba    | ✅        | ✅            | ✅           | ✅       | ✅             |
| UV            | ✅        | ⚪            | ✅           | ⚪       | ✅             |
| Poetry        | ✅        | —             | —            | —        | ✅             |

> Creation + package support expands in v0.6.x.

---

## 📦 Downloads
Download the latest version:

👉 https://pyenvmanager.com/releases.html

- **Windows (x64)** — `.exe` installer  
- **macOS (ARM64 + x64)** — notarized `.dmg`  
- **Linux** — `.AppImage`

---

## 🚀 Quick Start

### Installation
1. Download the installer for your platform
2. Run the installer (Windows/macOS) or make executable (Linux)
3. Launch PyEnvManager

### First Steps
1. **Scan for environments** — Click "Refresh" to discover all Python environments
2. **Create an environment** — Click "+" to create venv or Mamba environments
3. **Manage packages** — Click any environment to view/install/remove packages
4. **Run security scan** — Use automated scan for vulnerability analysis
5. **Open directories** — Quick access to environment folders

---

---

## 🐛 Feedback & Support

### Report Issues
Found a bug? Have a feature request?  
👉 https://github.com/Pyenvmanager/pyenvmanager-releases/issues

### Known Issues (v0.5.6)
- None currently reported

### Recent Fixes
- ✅ Git-based project grouping now works immediately on launch
- ✅ Environment deletion properly cleans up all cache files
- ✅ MODERATE severity CVEs correctly classified
- ✅ venv creation works with all Python installations

---

## ❤️ Contributing

We welcome:
- 🐛 Bug reports  
- 💡 Feature suggestions  
- 📖 Documentation improvements  
- 🧪 Environment compatibility feedback  
- 🔧 Code contributions (coming soon)

> Contribution guidelines coming soon.

---

## 🔒 Security

PyEnvManager takes security seriously:
- 🔍 **Vulnerability scanning** using industry-standard OSV database
- 🛡️ **Accurate CVE classification** with proper severity mapping
- 📄 **SBOM generation** for compliance and auditing
- 🔐 **Secure deletion** with proper cache cleanup
- 📊 **Professional reports** for security teams

Report security vulnerabilities privately through our GitHub security advisories.

---

## 📊 Statistics (v0.5.6)

- **Environments Supported:** 6 types (venv, Conda, Mamba, Micromamba, UV, Poetry)
- **Python Versions:** 3.7 → 3.13
- **Platforms:** Windows, macOS (Intel + ARM), Linux
- **Package Managers:** pip, conda, mamba, micromamba
- **Security Database:** OSV (constantly updated)

---

## 🗺️ Roadmap

### Coming in v0.6.x
- 🔄 Environment drift detection (side-by-side diff)
- 🔄 Enhanced environment cloning features
- 📦 Extended package manager support (UV, Poetry creation)
- 🚀 Improved SBOM export capabilities
- 📊 Fleet dashboard integration
- 🔍 Advanced dependency analysis
- ⚡ Performance optimizations for large environment sets

### Long-term Goals
- Cloud sync for environment configurations
- Team collaboration features
- CI/CD integration
- Package vulnerability alerts
- Automated remediation suggestions

---

## 🏆 Why PyEnvManager?

| Feature | PyEnvManager | Conda/Mamba CLI | venv | Others |
|---------|-------------|-----------------|------|--------|
| **Universal Environment Discovery** | ✅ (includes shadow binaries) | ❌ | ❌ | ⚪ |
| **Zero-Friction Agent** | ✅ (Rust-powered, no perf impact) | ❌ | ❌ | ⚪ |
| **One-Click Activation** | ✅ | ❌ | ❌ | ❌ |
| **Visual Interface** | ✅ | ❌ | ❌ | ⚪ |
| **Multi-Manager Support** | ✅ (venv, conda, mamba, poetry, UV) | ❌ | ❌ | ⚪ |
| **Shift-Left Security** | ✅ (CVE + License scanning) | ❌ | ❌ | ❌ |
| **Environment Drift Detection** | ✅ (side-by-side diff) | ❌ | ❌ | ❌ |
| **Git-Based Organization** | ✅ (automatic) | ❌ | ❌ | ❌ |
| **SBOM Generation** | ✅ (HTML/JSON) | ❌ | ❌ | ❌ |
| **Self-Audit Reports** | ✅ | ❌ | ❌ | ❌ |
| **Jupyter Integration** | ✅ (one-click launch) | ⚪ | ⚪ | ⚪ |
| **Cross-Platform** | ✅ | ✅ | ✅ | ⚪ |




---

**Version:** 0.5.6  
**Released:** January 31, 2026  
**Website:** https://pyenvmanager.com  
**GitHub:** https://github.com/Pyenvmanager
