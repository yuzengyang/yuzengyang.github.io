# Zengyang Yu — Personal Website

Personal academic homepage of Zengyang Yu (于增洋), Ph.D. candidate in
Theoretical Economics at the Jinhe Center for Economic Research,
Xi'an Jiaotong University.

Live at <https://yuzengyang.github.io/>.

## Pages

- `index.html` — Home: photo, contact info, bio, education, news, acknowledgments
- `research.html` — Research: publications, working papers, work in progress, presentations
- `css/style.css` — shared stylesheet (Morandi blue theme)
- `images/photo.jpg` — profile photo
- `favicon.svg` — site icon (geometric "Y" mark)

Both pages share navigation and footer markup; the active nav link is marked
with `class="active"`, and a small inline script toggles `.nav--scrolled` on
scroll and sizes the news / publications scroll containers.

## Local preview

```bash
python -m http.server 8000
# then open http://localhost:8000
```

## Deploy

The repository is named `yuzengyang.github.io`, so GitHub Pages serves the
default branch (`main`) at the site root with no build step.

```bash
git add -A
git commit -m "update: ..."
git push origin main
```

Changes go live about one to two minutes after a push.

## Notes

- Theme: Morandi blue (`:root` variables in `css/style.css`); every colour is
  taken from that palette.
- Publication details (journal, volume, article number, DOI) match the
  publisher records; links resolve to the DOI landing pages.
- When the content changes, update the `Last updated` date in the footer of
  both pages.
