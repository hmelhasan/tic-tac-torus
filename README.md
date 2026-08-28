# Tic Tac Torus

A three-player, four-in-a-row game on a 5 × 9 toroidal grid. Play proceeds in
the order X → O → △. Horizontal, vertical, and diagonal winning lines may wrap
across the left/right or top/bottom edges.

The entire game is contained in `index.html`. It has no dependencies, package
manager, build process, or server-side code.

## Run locally

Open `index.html` in a modern web browser.

## Publish with GitHub Pages using only the website

1. Create a new GitHub repository, such as `tic-tac-torus`.
2. Upload `index.html` and this `README.md` to the repository's `main` branch.
3. Open the repository's **Settings**.
4. Select **Pages** in the sidebar.
5. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
6. Select the `main` branch and the `/(root)` folder, then click **Save**.
7. After GitHub finishes deploying, the project site will normally be available
   at `https://YOUR-USERNAME.github.io/tic-tac-torus/`.

## Publish from the command line

First create an empty repository named `tic-tac-torus` on GitHub. Then, from
this project directory, run:

```bash
git init
git add index.html README.md
git commit -m "Publish Tic Tac Torus"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/tic-tac-torus.git
git push -u origin main
```

Then enable GitHub Pages under **Settings → Pages** using `main` and `/(root)`.

## Editing the game

All page content, styles, and JavaScript are inside `index.html`:

- HTML begins near the `<body>` tag.
- CSS is inside the `<style>` element.
- Game rules and behavior are inside the `<script>` element.

After editing, commit and push the revised file. GitHub Pages will republish the
site automatically from the configured branch.
