# Save the Research Lab

A self-contained, static psychology research methods practice game. It includes the Beginner, Intermediate, and Advanced levels (20 questions each), immediate explanatory feedback, five lab repairs, and the original pixel-art graphics. No server, database, API key, login, build step, or package installation is required. Answers and progress exist only in the open browser session.

## Files

- `index.html` — game interface, styling, and interaction code
- `levels.js` — all 60 questions, choices, explanations, and level definitions
- `neuroscience-lab-pixel.png` — current laboratory artwork
- `research-lab-pixel.png` — earlier artwork retained with the complete source; it is not used by the current page
- `.nojekyll` — tells GitHub Pages to serve these files directly

All paths in the page are relative, so the game works at a GitHub Pages project URL such as `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Try it before publishing

Extract the ZIP and open `index.html` in a browser. Alternatively, from this folder run `python3 -m http.server 8000`, then visit `http://localhost:8000/`. The Python command is only for local preview; it is not required on GitHub Pages.

## Publish on GitHub Pages (free public repository)

1. Create a **public** repository on GitHub, for example `save-the-research-lab`. Initialize it with a README so the default branch exists. GitHub Free supports Pages for public repositories.
2. Create a new branch such as `import-research-lab` from the default branch. Extract this ZIP and upload its **contents** to that branch's repository root. `index.html` must be at the root, alongside `levels.js` and the PNG files; do not upload the ZIP itself or put the files inside an extra folder. Replace the starter README with this one.
3. Open a pull request from `import-research-lab` into the default branch. Review the files and merge the pull request when ready. Do not commit the import directly to the default branch.
4. In the repository, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose the default branch and **/(root)**, then **Save**.
5. Once GitHub finishes publishing, use **Settings → Pages → Visit site**. A project site normally has the address `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

For later edits, create another feature branch, open a pull request, and merge only after review. GitHub Pages will publish the merged version from the selected branch. To undo an update, revert its merge commit through a new pull request; the previous version will publish again.

GitHub documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site and https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
