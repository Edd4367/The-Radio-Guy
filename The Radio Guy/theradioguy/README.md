# The Radio Guy — Artist Website

A single-page website for **The Radio Guy**, a lofi music project whose mascot is a walking boombox. Built around the character artwork and the cover of the debut album, *Musical Theory*.

## Live preview

Open `index.html` in any browser — no build step or server required.

## What's inside

```
the-radio-guy-site/
├── index.html          # the whole site (HTML + CSS + JS in one file)
├── assets/
│   ├── character.png   # mascot artwork (hero section)
│   └── cover.jpg        # "Musical Theory" album cover
└── README.md
```

## Design

- **Palette** — cream, ink black, mustard gold and terracotta, pulled straight from the album cover.
- **Type** — `Bebas Neue` for headlines (broadcast/radio feel) and `Space Mono` for body text and labels (typewriter/cassette feel).
- **Signature details** — a scrolling radio-style ticker in the hero, a spinning "cassette tape" card in the About section, and preset-style buttons (like radio dial buttons) for the streaming links.
- Fonts are loaded from Google Fonts via CDN, so an internet connection is needed to see them rendered correctly; the site still works offline with browser fallback fonts.

## Sections

1. **Hero** — artist name, tagline, mascot artwork, "Listen now" CTA.
2. **About** — short bio and quick stats.
3. **Music** — embedded Spotify player for the *Musical Theory* album.
4. **Listen everywhere** — links to Spotify, YouTube and Instagram.
5. **Footer** — repeated social links.

## Links used

- Spotify: https://open.spotify.com/intl-pt/album/2nUrpWGz0ezPtVM7cQ10cI
- YouTube: https://www.youtube.com/@TheRadioGuy440hz
- Instagram: https://www.instagram.com/theradioguymusic/

To update any of these, search for the URL inside `index.html` (it appears in the nav button, the hero CTA, the "Listen everywhere" cards, and the footer) and replace it.

## Editing content

Everything is in `index.html`:

- **Bio text** — inside `<section class="section" id="sobre">`.
- **Album description** — inside `<section class="section music-section" id="musica">`.
- **Colors** — CSS custom properties at the top of the `<style>` block (`:root { ... }`).
- **Images** — swap the files in `assets/` and keep the same filenames, or update the `src` attributes in `index.html`.

## Deploying

This is a static site, so it can be hosted anywhere that serves static files:

- **Netlify / Vercel** — drag and drop the `the-radio-guy-site` folder (or connect a Git repo).
- **GitHub Pages** — push the folder to a repo and enable Pages on the branch.
- **Any static host** — just upload the whole folder, keeping `index.html` and `assets/` together.

## Credits

- Character and album artwork provided by the artist.
- Fonts: [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue) and [Space Mono](https://fonts.google.com/specimen/Space+Mono) via Google Fonts.
