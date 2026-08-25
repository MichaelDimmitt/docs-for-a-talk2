---
description: Branching, commit, PR/merge, and architecture-doc workflow rules for this repo.
alwaysApply: true
---

# Workflow

- Commit after every change.
- Branch before the first commit. Any time the repo is in a clean state and new work begins, create and check out a new branch immediately — before making any changes. Never commit feature work directly to `main`.
- PR and merge flow: When the user asks to PR and merge, push the branch, create the PR, squash merge it, then sync local `main` with `git reset --hard origin/main`. Do NOT use `git pull --rebase` — squash merges diverge the history and cause rebase conflicts every time.
- Keep `TECHNICAL-ARCHITECTURE-LEGACY.md` up to date for changes in `src/websites/` (legacy HTML app). After the Vercel port lands, a new `TECHNICAL-ARCHITECTURE.md` covers the Next.js structure.

# Git LFS

- PDF files are tracked via Git LFS (see `.gitattributes`).
- On session start, check `git status` for any LFS-tracked files shown as deleted or missing. If found, check whether `git lfs` is installed; if not, prompt the user to run `brew install git-lfs && git lfs install`, then run `git lfs pull`. Do this before any other work.
