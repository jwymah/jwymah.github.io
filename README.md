# SpdCoach GPS dashboard

A dependency-free static site combining:

- the eight-segment session summary;
- the interactive GPS speed overlay;
- the synchronized GPS race animation; and
- the downloadable Excel workbook.

## Publish with GitHub Pages

1. Create a new GitHub repository, such as `spdcoach-race`.
2. Upload every file in this folder to the repository root.
3. Commit the files to the `main` branch.
4. Open **Settings → Pages** in the repository.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Choose the `main` branch and `/ (root)`, then save.

GitHub will display the public URL after deployment, normally:

```text
https://YOUR-USERNAME.github.io/spdcoach-race/
```

## Local preview

From this folder, run:

```bash
python3 -m http.server 8765
```

Then open `http://localhost:8765`.

No build step or third-party dependency is required.
