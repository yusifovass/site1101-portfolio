# Student Portfolio — Static Site

This is a small, static personal portfolio site made with HTML, CSS, and a tiny amount of vanilla JavaScript.

Design idea:
- Colors: Neutral background with teal accent (variables in `assets/css/style.css`).
- Typography: Inter for a modern, legible look.
- Layout: Split hero with photo + intro on larger screens; stacked on smaller screens. Projects in a responsive grid.

How to run locally (VSCode + Live Server):
1. Install the Live Server extension in VSCode.
2. Open the workspace root in VSCode.
3. Right-click `index.html` and choose "Open with Live Server".
4. The site will load at `http://127.0.0.1:5500` (or similar)

Git / GitHub steps (basic):
1. Initialize a repository and make commits:
```
git init
git add .
git commit -m "Initial commit: static portfolio"
```
2. Create a repository on GitHub and push:
```
git remote add origin https://github.com/yusifovass/site1101-portfolio.git
git branch -M main
git push -u origin main
```
3. Enable GitHub Pages in your repository settings. Set the source to `main` (root) or `gh-pages` branch.

Notes:
- Replace placeholder text and SVGs in `assets/img/` with your own content.
- All links between pages are relative, so this will work on GitHub Pages.
- Keep styles modular and add comments for any customizations.

Good luck — export this chat for your assignment and update the content with your real info!
