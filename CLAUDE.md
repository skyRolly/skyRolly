# CLAUDE.md

Guidance for AI assistants working in this repository.

## What this repository is

This is the **GitHub special profile repository** for the user `skyRolly`
(repo `skyRolly/skyRolly`). Because the repo name matches the username, the
root `README.md` is rendered on the user's public GitHub profile page.

There is **no application code, build system, package manager, or test suite**
here. The "deliverable" is the profile `README.md` and an optional GitHub Pages
site built from the repository's Markdown.

## Layout

```
README.md                          # Profile README — shown on the GitHub profile page
CLAUDE.md                          # Repository maintenance guidance
```

## How content is published

- **Profile page**: GitHub renders `README.md` directly on
  `https://github.com/skyRolly`. Any push to `main` updates it.
- **GitHub Pages**: GitHub's built-in `pages build and deployment` workflow
  builds and deploys the `main` branch using Jekyll. The repository's Pages
  publishing source is managed by GitHub; no custom Actions workflow is needed.
  - There is no `_config.yml` or other Jekyll source, so the build uses defaults.


## Conventions

- **Default branch is `main`.** Pages publishes from `main` through GitHub's built-in workflow.
- Keep `README.md` profile-appropriate — it is public and the first thing
  visitors see. Edits are content/copy changes, not code.
- The HTML comment block at the top of `README.md` is GitHub's profile-repo
  hint and is not rendered; leave it unless intentionally cleaning up.
- This is a Markdown/content repo. Use the Markdown tooling and prose
  conventions appropriate to a profile README rather than software engineering
  patterns.

## Working here

- No install, build, lint, or test commands exist or are needed for local edits.
- To preview Pages output you would render the repo with Jekyll locally, but for
  simple README edits the GitHub-rendered preview is sufficient.
- After a push to `main`, check that GitHub's `pages build and deployment` workflow succeeds.
- Do not add a second Pages deployment workflow unless the publishing source and deployment approach are intentionally changed.
