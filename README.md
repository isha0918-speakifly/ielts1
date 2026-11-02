# Speakifly – IELTS Reading Practice

Static website (no build step). 10 passages, 3 questions each, 20-minute timer, instant scoring, progress saved in the browser.

## Publish on GitHub Pages
1. Create a repository and upload `index.html`, `README.md` and the `assets/` folder.
2. Settings → Pages → Source: `main` branch, `/ (root)` → Save.
3. Your site appears at `https://<username>.github.io/<repo>/`.

## Add or edit passages
Edit the `DATA` array in `index.html`.
- True/False/Not Given: `["statement", 0]` (0 = True, 1 = False, 2 = Not Given)
- Multiple choice: `["question", ["a","b","c"], 1]` (last number = index of the correct option)
