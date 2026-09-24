<<<<<<< HEAD
# l-red.github.io
=======
# Liam’s personal page

A standalone static page for GitHub Pages. No build step or JavaScript required.

## Preview locally

```sh
python3 -m http.server 4175 --bind 127.0.0.1
```

Open http://127.0.0.1:4175.

## Publish on GitHub Pages

For a profile site, use a repository named `L-Red.github.io`. Put the contents of this directory at its root. In the repository’s **Settings → Pages**, choose **Deploy from a branch**, then the publishing branch and **/ (root)**. The resulting URL is `https://l-red.github.io/`.

The page also works in a project repository because all asset paths are relative. The local preview files have not been published or pushed.

## Content and type

Edit the text and links in `index.html`; presentation is in `style.css`. The name, background, and location come from [Liam’s public GitHub profile](https://github.com/L-Red).

[Sixtyfour Convergence](https://fonts.google.com/specimen/Sixtyfour+Convergence), by Simon Cozens and Jens Kutílek, is served locally under the SIL Open Font License. The original license is included at `assets/fonts/OFL.txt`. Its second built-in palette is used against the dark background. Browsers without color-font support fall back to the font’s monochrome glyphs or the system monospace font.
>>>>>>> 10db629 (Initial Push)
