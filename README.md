> [!NOTE]
> This project is a fork of [remote-cli/remote](https://github.com/remote-cli/remote). The original project and its contributors can be found there.

# Remote

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![CI/CD Status](https://github.com/wesship/remote/actions/workflows/ci.yml/badge.svg)](https://github.com/wesship/remote/actions/workflows/ci.yml)

> A CLI tool that lets you execute long or computation-heavy tasks on a powerful remote host while you work on the source code locally. It syncs your workspace, executes the command remotely, and brings back the results.

---

## ✨ Features

- **Remote Execution**: Run commands on a remote host seamlessly.
- **Workspace Sync**: Automatically syncs your local workspace to the remote host and back.
- **Customizable Configuration**: Fine-tune sync and execution behavior with a simple TOML configuration.
- **Multi-Host Support**: Work with multiple remote hosts and switch between them easily.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.6+
- A remote host accessible via SSH

### Installation

On macOS, you can install `remote` using Homebrew:

```bash
brew install remote-cli/remote/remote
```

For other systems, you can download the latest release from the [releases page](https://github.com/remote-cli/remote/releases).

### Usage

1. Initialize the remote in your workspace:
   ```bash
   remote-init your-remote-host.example.com
   ```
2. Run a command remotely:
   ```bash
   remote ./gradlew build
   ```

---

## 🛠️ Built With

- [Python](https://www.python.org/)

---

## 🤝 Contributing

Contributions are welcome! Please see the [contributing guidelines](CONTRIBUTING.md) for more information.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
