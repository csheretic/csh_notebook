# Contributing

Thank you for helping improve csh_notebook documentation.

## Make a change

1. Create a branch for your change.
2. Edit or add Markdown pages in `docs/`. Keep names lowercase and
   hyphen-separated, and add an `index.md` to each new documentation folder.
3. Preview and validate the site:

   ```sh
   python -m pip install -r requirements.txt
   mkdocs serve
   mkdocs build --strict
   ```

4. Open a pull request with a concise summary and any relevant context.

## Writing guidelines

- Write for the reader's task and use clear, direct language.
- Add links between related pages and check that relative links work.
- Keep repository contributor instructions in `README.md` and user-facing
  content in `docs/`.
- Store images in `assets/images/` and reusable page layouts in
  `assets/templates/`.
- Use `docs/<section>/index.md` as the landing page for each section.

The Markdown lint workflow runs automatically for pull requests.
