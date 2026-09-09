# Contributing to zo-snapshot

PRs from forks are welcome. You do not need write access to this repo.

## Fork → branch → PR

1. Click **Fork** on https://github.com/SillyHippy/zo-snapshot (creates `YOUR_USER/zo-snapshot`).
2. Clone your fork:

   ```bash
   git clone https://github.com/YOUR_USER/zo-snapshot.git
   cd zo-snapshot
   git remote add upstream https://github.com/SillyHippy/zo-snapshot.git
   ```

3. Create a branch from `main`:

   ```bash
   git checkout main
   git pull upstream main
   git checkout -b your-change
   ```

4. Commit, push to **your fork**, then open a Pull Request:

   ```bash
   git push -u origin your-change
   ```

   GitHub will show **Compare & pull request**. Target:

   - base repo: `SillyHippy/zo-snapshot`
   - base branch: `main`
   - head: `YOUR_USER:your-change`

Direct URL after you push:

`https://github.com/SillyHippy/zo-snapshot/compare/main...YOUR_USER:your-change`

## What to include

- One change per PR when you can.
- Keep the engine stdlib-only (no new pip deps) unless the PR is explicitly about packaging.
- If you touch CLI/API behavior, say what you ran (`zo-snapshot list`, a create/diff, etc.).

## Issues

Bugs and feature requests: https://github.com/SillyHippy/zo-snapshot/issues
