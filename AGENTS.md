# Repository workflow

This repository contains the “熊猫家宴” website.

For every change to this project:

1. Before editing, inspect the working tree with `git status`.
2. If the working tree is clean, run `git pull --rebase` to get the latest remote version before making changes.
3. If local uncommitted changes exist, preserve them. Do not overwrite, reset, or discard them just to pull; reconcile safely first.
4. After editing, verify the relevant website behavior and preview the result for the user.
5. Stage only the intended project changes, create a descriptive Git commit, and push the current branch to `origin` automatically.
6. Never commit credentials, tokens, downloaded secrets, or unrelated user files.

