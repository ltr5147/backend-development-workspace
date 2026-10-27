# Git Command Reference

## First-time setup

Replace the example email with the email associated with my GitHub account, or my GitHub-provided private email.

```bash
git config --global user.name "Logan Runyan"
git config --global user.email "YOUR_GITHUB_EMAIL"
```

## Everyday workflow

| Command | Purpose |
| --- | --- |
| `git clone REPOSITORY_URL` | Download a repository and its history. |
| `git status` | Check the branch and changed files. |
| `git diff` | Review unstaged changes. |
| `git add README.md` | Stage a specific file. |
| `git add .` | Stage changes in the current directory and its subdirectories. |
| `git diff --staged` | Review the changes prepared for a commit. |
| `git commit -m "Describe the change"` | Save staged changes in local history. |
| `git pull --ff-only` | Bring in remote changes when a fast-forward is possible. |
| `git push` | Upload local commits to the configured remote branch. |
| `git log --oneline` | View a compact commit history. |

## Branches and corrections

| Command | Purpose |
| --- | --- |
| `git switch -c feature-name` | Create a branch and switch to it. |
| `git switch main` | Return to the main branch. |
| `git restore --staged FILE` | Unstage a file while keeping its edits. |
| `git revert COMMIT_HASH` | Create a new commit that reverses an earlier commit. |
| `git remote -v` | Check remote repository addresses. |

## Commit reminders

- Keep each commit focused on one meaningful change.
- Use messages that explain what changed.
- Review staged changes before committing.
- Never commit passwords, access tokens, or secret environment files.
- Commit locally, then push to GitHub to back up and share the history.
