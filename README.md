# csh_notebook

This repository contains the source for the csh_notebook documentation site.
The published documentation is for end users; this README is for contributors.

## Work on the documentation

1. Install Python 3 and the project dependencies:

   ```sh
   python -m pip install -r requirements.txt
   ```

2. Start the local preview:

   ```sh
   mkdocs serve
   ```

3. Open the local URL printed by MkDocs, make changes under `docs/`, and
   submit a pull request.

Build the site locally with `mkdocs build --strict`. The generated site is
written to `site/` and is not committed.

See [CONTRIBUTING.md](CONTRIBUTING.md) for writing and review guidance.

## Repository layout

- `docs/` contains end-user documentation, organized by user journey and
  information type.
- `assets/` contains images and reusable page templates.
- `.github/workflows/` contains Markdown quality checks and site deployment.
- `mkdocs.yml` configures the documentation site.

## License

See [LICENSE](LICENSE) for the current licensing status.
