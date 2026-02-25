# Contributing to ODefender Community

Thank you for considering contributing! Every contribution helps security teams worldwide. 🛡️

## 🌟 How to Contribute

### 🐛 Bug Reports
- Check existing issues first
- Include: PowerShell version, OS, MDE license, steps to reproduce
- Remove any sensitive data from logs before posting

### 💡 Feature Requests
- Open an Issue with `[Feature Request]` prefix
- Describe the use case, expected behavior, and why it's useful

### 🔧 Code Contributions

1. **Fork** the project repository
2. **Create a branch**: `git checkout -b feature/my-feature`
3. **Follow** the coding standards below
4. **Test** your changes with `reportOnly` mode
5. **Commit**: `git commit -m "feat: description"`
6. **Push** and create a Pull Request

### 📝 Documentation
Documentation improvements are always welcome — typos, clarifications, translations, examples.

## 📋 Coding Standards

### PowerShell
- **PascalCase** for functions: `Get-ServerClassification`
- **camelCase** for variables: `$serverList`
- **UPPER_SNAKE_CASE** for constants: `$MAX_RETRIES`
- Always use `[CmdletBinding()]` for advanced functions
- Include comment-based help (`<# .SYNOPSIS #>`)
- Never hardcode credentials or tenant-specific values

### Commit Messages
Follow [Conventional Commits](https://www.conventionalcommits.org/): `feat:`, `fix:`, `docs:`, `refactor:`, `test:`, `chore:`

## 🔒 Security
Found a vulnerability? **DO NOT** open a public issue. See [SECURITY.md](SECURITY.md).

## 📜 License
By contributing, you agree your contributions will be licensed under [MIT](LICENSE).
