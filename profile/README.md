# Magic Scripts

**Developer automation made simple.**

Transform your repetitive development tasks into reusable command-line tools. Magic Scripts provides a unified system for managing, sharing, and running automation scripts across your projects.

*Built with the Unix philosophy: simple tools that do one thing well.*

## ✨ What is Magic Scripts?

Magic Scripts is a command-line ecosystem that lets anyone easily:

- **Create** automation scripts for common development tasks
- **Share** scripts through simple registry files 
- **Install** and manage scripts from multiple sources
- **Configure** scripts through a unified config system

## 🚀 Get Started in 30 Seconds

```bash
# Install latest stable version
curl -fsSL https://raw.githubusercontent.com/magic-scripts/ms/main/setup.sh | sh

# Install useful tools
ms install gigen licgen projinit

# Generate a .gitignore for your Node.js project
gigen add node

# Create an MIT license
licgen mit

# Initialize a new React project
projinit react my-app
```

## 📦 Installation Options

```bash
# Latest stable version (recommended)
curl -fsSL https://raw.githubusercontent.com/magic-scripts/ms/main/setup.sh | sh

# Specific version
curl -fsSL https://raw.githubusercontent.com/magic-scripts/ms/main/setup.sh | sh -s -- -v 0.0.1

# Development version (latest features)
curl -fsSL https://raw.githubusercontent.com/magic-scripts/ms/main/setup.sh | sh -s -- -v dev

# Using wget instead of curl
wget -qO- https://raw.githubusercontent.com/magic-scripts/ms/main/setup.sh | sh
```

## 🎯 Why Magic Scripts?

- **No more copy-pasting scripts** between projects
- **One command** to install and manage all your automation tools
- **Sharable registries** - distribute your team's scripts easily
- **Unified configuration** - set your name, email, etc. once
- **Version management** - keep your scripts up to date

## 🗑️ Uninstallation

```bash
# Normal uninstallation (recommended)
ms uninstall ms
```

### Emergency Cleanup

If Magic Scripts is corrupted or not working properly:

```bash
# Complete system cleanup (when ms command fails)
curl -fsSL https://raw.githubusercontent.com/magic-scripts/ms/main/cleanup.sh | sh
```

## 📚 Learn More

- **[Main Repository](https://github.com/magic-scripts/ms)** - Complete guide and reference
- **[Template Repository](https://github.com/magic-scripts/ms-template)** - Create your own scripts

---

*Join thousands of developers streamlining their workflows with Magic Scripts.*
