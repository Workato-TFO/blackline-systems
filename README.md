# BlackLine Systems Integration Bootcamp — Lab Guides

Lab guides for the BlackLine Systems Integration Bootcamp, served via GitHub
Pages from the `docs/` folder (branch `main`, folder `/docs`).

## Labs

The four labs run in order. Each one starts from the project the previous lab
leaves behind.

| Lab | Tier | Time |
|---|---|---|
| [1 · Recipe refactoring](docs/blackline-recipe-refactoring.html) | Intermediate | 60 minutes |
| [2 · Project organization](docs/blackline-workspace-organization.html) | Intermediate | 20 minutes |
| [3 · Error handling](docs/blackline-error-handling.html) | Intermediate | 60 minutes |
| [4 · Recipe optimization](docs/blackline-recipe-optimization.html) | Intermediate | 45 minutes |

The course hub ([docs/index.html](docs/index.html)) links to all four.

## Structure

- `docs/` — the published surface: the course hub plus one self-contained
  page per lab (Pages source)
- Every commit is checked by the publish guard workflow
  (`.github/workflows/publish-guard.yml`); the same checks run locally as a
  pre-push hook — enable once per clone with:

```
git config core.hooksPath .githooks
```

## Contributing

Content is authored and reviewed elsewhere; this repo holds only pressed,
vetted output. Do not edit lab HTML in place — changes land as a fresh press
of the whole bundle.
