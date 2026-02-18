# musicofthings.github.io

Minimal static portfolio site for GitHub Pages.

## Local preview

```bash
python3 -m http.server 4173
```

Then open `http://127.0.0.1:4173`.

## Codex Web → GitHub sync workflow

Because this is edited through Codex Web, changes still need to be synced to GitHub to trigger GitHub Pages:

1. Commit changes in the Codex workspace branch.
2. Open/create the PR from that branch.
3. Merge the PR into the branch configured in **Settings → Pages** (usually `main`).
4. Wait for Pages deployment to finish, then hard-refresh the site.
