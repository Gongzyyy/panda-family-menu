# Repository workflow

This repository contains the “熊猫家宴” website.

For every change to this project:

1. Before editing, inspect the working tree with `git status`.
2. If the working tree is clean, run `git pull --rebase` to get the latest remote version before making changes.
3. If local uncommitted changes exist, preserve them. Do not overwrite, reset, or discard them just to pull; reconcile safely first.
4. After editing, verify the relevant website behavior and preview the result for the user.
5. Stage only the intended project changes, create a descriptive Git commit, and push the current branch to `origin` automatically.
6. Never commit credentials, tokens, downloaded secrets, or unrelated user files.

## Ongoing quality and design

- PM: Before handing off a website change, verify the affected flow and report concrete results and anything unverified. For catalog changes, check for duplicates, category and ingredient mappings, and the correct image for each new dish. For interface changes, check search, filters, ingredient matching, favorites, selection, menu generation, and image export where affected.
- UX designer: For interface changes, review the journey on mobile and desktop. Keep the restrained Chinese restaurant menu style and the continuous browsing flow. Prioritize readable dish cards, easy access to search and favorites, prompt ingredient-match feedback, and clear selection and export controls. Show a separate Chrome preview for substantial visual redesigns so the owner can review the direction.
- When independent role reviews are requested, use a PM reviewer and a UX reviewer on the same revision. Include the relevant review findings in the handoff.

