# KayaHarper.github.io
# Kaya Harper — Personal Academic Website

A single-page personal website for Kaya Harper, PhD Candidate in Biology at Texas A&M University.

## Structure

```
/
├── index.html
├── assetts/
│   └── photos/
│       ├── IMG_1160.jpg        # Profile photo (home page)
│       └── IMG_2141.jpg        # Background photo
└── pictures/                   # Gallery images
```

## Pages

| Tab | Content |
|-----|---------|
| **Home** | Photo and short bio |
| **About** | Research interests, lab affiliations (Blackmon & Keene labs), rotating current projects |
| **Education & Experience** | Degrees, teaching, mentorship, grants, service, awards |
| **Pictures** | Photo gallery with lightbox viewer |
| **Get in Touch** | Contact details and social/professional links |

## Updating Content

All content lives in `index.html` — no build tools or dependencies required.

- **Bio** — edit the `<p>` tags inside `<div id="home">`
- **Current projects** — edit the `.project-slide` divs inside `<div id="about">`; the carousel rotates automatically every 3 seconds
- **Gallery photos** — add or remove `<div class="gallery-item">` entries inside `<div id="pictures">`; broken images hide themselves automatically
- **Contact info** — update the `.contact-row` entries inside `<div id="contact">`

## Notes

- No frameworks, build steps, or dependencies — open `index.html` directly in a browser
- The background and profile photo use relative paths; keep the `assetts/` and `pictures/` folders alongside `index.html`
- Gallery supports JPEG, JPG, PNG, HEIC, and PNG formats
- The lightbox supports keyboard navigation (← → arrow keys, Esc to close)