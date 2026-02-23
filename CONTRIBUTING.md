# Contributing to TeQoin Documentation

Thank you for contributing to TeQoin's documentation! 🎉

## 🤝 Code of Conduct

Be respectful, inclusive, and professional in all interactions.

## 🚀 Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/YOUR_USERNAME/docs.git`
3. Create a feature branch: `git checkout -b feature/your-feature`
4. Make changes
5. Test locally: `mintlify dev`
6. Submit a pull request

## 🌿 Branch Naming Convention

| Prefix | Purpose | Example |
|--------|---------|---------|
| `feature/` | New content or features | `feature/api-reference` |
| `docs/` | Documentation updates | `docs/fix-typos` |
| `fix/` | Bug fixes | `fix/broken-links` |
| `style/` | Formatting/design | `style/update-colors` |

## 📝 Commit Message Format

We follow [Conventional Commits](https://www.conventionalcommits.org/):
```
<type>(<scope>): <subject>

<body> (optional)
```

**Types:** `docs`, `feat`, `fix`, `style`, `refactor`, `test`, `chore`

**Examples:**
```bash
git commit -m "docs(api): add indexer endpoints documentation"
git commit -m "feat(tutorials): add smart contract deployment guide"
git commit -m "fix(quickstart): correct MetaMask network parameters"
```

## 🔄 Pull Request Process

1. Create PR to `develop` (not `main`)
2. Use conventional commit format for title
3. Describe changes clearly
4. List what you tested
5. Wait for review and approval

## 📚 Style Guide

### Writing

- **Clear and concise** - Avoid jargon
- **Active voice** - "Deploy the contract"
- **Present tense** - "The API returns"
- **Second person** - "You can deploy"

### Code Blocks

Always specify language:
```javascript
const provider = new ethers.JsonRpcProvider('https://rpc.teqoin.io');
```

## ✅ Checklist

- [ ] Code blocks have language specified
- [ ] All links work locally
- [ ] Tested with `mintlify dev`
- [ ] Follows conventional commits
- [ ] PR targets `develop` branch

Thank you for contributing! 🚀