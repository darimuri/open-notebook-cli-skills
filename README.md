# Open Notebook CLI Skills

Claude Code plugin for Open Notebook API.

## Installation

### Prerequisites

- [Open Notebook CLI](https://github.com/darimuri/open-notebook-cli) must be installed and accessible in PATH

### Install the Claude Code Plugin

```bash
claude plugin marketplace add darimuri/open-notebook-cli-skills
claude plugin install open-notebook@open-notebook-cli-skills
```

After installation, run `/reload-plugins` to activate, then use `/open-notebook` commands in Claude Code.

### Install Open Notebook CLI

If you haven't installed the CLI yet:

**Linux/macOS:**
```bash
curl -sL https://raw.githubusercontent.com/darimuri/open-notebook-cli/main/install.sh | bash
```

**Windows:**
```powershell
irm https://raw.githubusercontent.com/darimuri/open-notebook-cli/main/install.ps1 | iex
```

**From source:**
```bash
git clone https://github.com/darimuri/open-notebook-cli.git
cd open-notebook-cli
go build -o open-notebook ./main.go
# Add to PATH or use ./open-notebook
```

**Manual download:**
Download from https://github.com/darimuri/open-notebook-cli/releases/latest

## Usage

See `/open-notebook` in Claude Code for available commands, or see the [SKILL.md](skills/open-notebook/SKILL.md) for full documentation.

## Version Management

When a new version is released, run the **Update Skill Versions** workflow on GitHub Actions with the version tag (e.g., `v0.0.8`).

## License

MIT
