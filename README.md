# koszcz.github.io

This is the personal page of Konrad Szczęśniak, a senior full stack engineer in Warsaw.

**See it live:** https://koszcz.github.io/

The page has:

- a short intro with a photo and links to LinkedIn and GitHub
- an About section
- Hitoria, my open source browser game
- my work experience

It follows your system's dark or light mode, and it works on phones.

## Files

| File         | What it holds                         |
| ------------ | ------------------------------------- |
| `index.html` | All the page content                  |
| `style.css`  | All the styles, including dark mode   |
| `avatar.jpg` | The profile photo                     |

The page is plain HTML and CSS. It has no build step and no dependencies.

## Preview the page on your computer

1. Open a terminal in this folder.
2. Start a local web server:

   ```bash
   python3 -m http.server 8123
   ```

3. Open http://localhost:8123 in your browser.

## Publish a change

1. Commit your change.
2. Push it to the `main` branch.

GitHub Pages builds the site from `main`. The live page updates within a minute or two.
