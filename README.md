# Homebrew Tap for jctl

Official Homebrew tap for [jctl](https://github.com/avidala/jctl) - Jenkins Control CLI with Okta SSO.

Part of the AVIDALA DevOps Tools suite.

## Installation

```bash
brew install avidala/jctl/jctl
```

Or tap first, then install:

```bash
brew tap avidala/jctl
brew install jctl
```

## Usage

After installation, run:

```bash
jctl --version
jctl --help
```

## Documentation

For complete documentation, configuration, and usage examples, visit the [main repository](https://github.com/avidala/jctl).

## Features

- 🔐 **Dual Authentication** - Okta OAuth 2.0 and API tokens
- 🚀 **Pipeline Control** - List, run, cancel, and monitor Jenkins pipelines
- 📋 **Job Management** - Trigger builds, view logs, check status
- 🔄 **Real-time Logs** - Stream build logs with color support
- 🎨 **Beautiful Output** - Rich terminal UI with tables and colors
- 🔒 **Secure Storage** - OS-native keychain integration
- ⌨️ **Shell Completion** - Tab completion for commands and options
- 🎯 **Multiple Profiles** - Manage multiple Jenkins environments

## Requirements

- macOS or Linux
- Python 3.10+

## Updating

To update to the latest version:

```bash
brew update
brew upgrade jctl
```

## Uninstalling

```bash
brew uninstall jctl
brew untap avidala/jctl
```

## Issues & Support

- Report issues: [GitHub Issues](https://github.com/avidala/jctl/issues)
- Main repository: [avidala/jctl](https://github.com/avidala/jctl)

---

**Built by AVIDALA** • DevOps Tools & Automation
