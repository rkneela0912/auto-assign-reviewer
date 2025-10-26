# Auto Assign Reviewer 👥

[![GitHub release](https://img.shields.io/github/v/release/rkneela0912/auto-assign-reviewer)](https://github.com/rkneela0912/auto-assign-reviewer/releases) [![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Intelligently assign reviewers

## Quick Start

```yaml
name: Auto Assign Reviewer
on:
  pull_request:
    types: [opened, synchronize]

jobs:
  run:
    runs-on: ubuntu-latest
    permissions:
      pull-requests: write
      issues: write
    steps:
      - uses: rkneela0912/auto-assign-reviewer@v1
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
```

## Features

- Automated GitHub Actions workflow
- Easy to configure
- Production-ready
- MIT licensed

## Inputs

| Input | Description | Required |
|-------|-------------|----------|
| `github_token` | GitHub token for API access | ✅ Yes |

## License

[MIT License](LICENSE)

## Support

⭐ Star this repo if you find it helpful!

For issues, [open an issue](https://github.com/rkneela0912/auto-assign-reviewer/issues).

## 💡 👥 Smart reviewer assignment

Make your workflow more efficient with automation!
