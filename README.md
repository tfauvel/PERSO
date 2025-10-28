# PERSO

## Create the `test` branch from scratch

1. Start from the `work` branch:
   ```bash
   git checkout work
   ```
2. Create the new branch locally:
   ```bash
   git checkout -b test
   ```
3. Push it to GitHub so it appears in the remote branch selector:
   ```bash
   git push -u origin test
   ```
   Replace `origin` with the name of your remote if it differs.
4. Confirm on GitHub that the `test` branch exists. The branch picker at the top left of the repo will now list `test`.
5. If ChatGPT (ChatCodex) is already open, use the branch dropdown's refresh action. The `test` branch is now selectable there as well because it exists on the remote.

## Switch between branches locally

Use `git checkout <branch-name>` (or `git switch <branch-name>`) to move between `work` and `test`.
