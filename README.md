# Circadia research workspace

Deploy `index.html` as a static GitHub Pages site. No dependencies, build system or server required.

## Publish on GitHub Pages

1. Create a repository, e.g. `circadia-workspace`.
2. Upload `index.html` to the repository root.
3. In **Settings → Pages**, select **Deploy from a branch**, `main`, `/ (root)` and save.
4. Share the GitHub Pages URL with your collaborator.

## Collaboration and persistence

Task updates, notes, meetings and the repository URL save in the browser's `localStorage` only. They are **not live synchronized** between browsers or users. Use **Export JSON snapshot** and **Import snapshot** to exchange current state. Import replaces all existing local workspace state, so export a backup first.

For genuine live collaboration, use GitHub Issues/Projects for tasks and pull requests for research decisions, or add an authenticated database backend later. Never put GitHub personal access tokens or private patient data in this static HTML file.

## Notes

- The demo is a nonclinical, exploratory study planning tool.
- NHANES work schedule is current while cancer diagnosis is lifetime history, creating temporal ambiguity.
- Dataset variables and survey methods must be independently validated before performing inferential analyses.
