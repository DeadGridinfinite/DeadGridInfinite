# Contributing to Dead Grid: Infinite Night

First off, thanks for taking the time to contribute! 🧟

## How to Contribute

1. **Fork** the repository.
2. **Create a branch** for your change:
   ```bash
   git checkout -b feat/your-feature-name
   ```
3. **Make your changes** in `index.html` (the game is a single self-contained file: HTML, CSS, and JS all live together).
4. **Test locally** by opening `index.html` directly in your browser — no build step needed.
5. **Commit** with a clear message:
   ```bash
   git commit -m "feat: add new zombie type"
   ```
6. **Push** and open a **Pull Request** against `main`.

## Ideas for Contributions

- New enemy types or boss waves
- Power-ups / weapon upgrades
- Sound effects & music
- Additional visual effects (screen shake, more particle variety)
- Performance improvements for low-end/mobile devices
- Accessibility improvements (colorblind-friendly palette, remappable controls)

## Code Style

- Keep the game dependency-free (vanilla HTML/CSS/JS).
- Match the existing neon/cyber-grid visual theme where possible.
- Comment non-obvious logic, especially in rendering and physics code.

## Reporting Bugs / Requesting Features

Please use the issue templates:
- [Bug Report](.github/ISSUE_TEMPLATE/bug_report.md)
- [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md)

## Code of Conduct

This project follows a [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to uphold it.
