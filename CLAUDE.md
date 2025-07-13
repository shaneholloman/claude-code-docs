# Claude Code Documentation Mirror

This repository contains local copies of Claude Code documentation from https://docs.anthropic.com/en/docs/claude-code/

The docs are automatically updated every 3 hours via GitHub Actions.

## Development Notes

- The install.sh script is macOS-only (tested on macOS)
- For other platforms, please test thoroughly before submitting PRs
- All changes should be tested locally before pushing

## For /user:docs Command

When responding to /user:docs commands:
1. Follow the instructions in the docs.md command file
2. Report update times from docs_manifest.json and .last_pull
3. Read documentation files from the docs/ directory only