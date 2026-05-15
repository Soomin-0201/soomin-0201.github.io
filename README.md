# Personal Site — GitHub Pages

A keyword-driven personal homepage for Soomin, built as a static `index.html` + `style.css`.

## Deploy to GitHub Pages

1. Create a new repo named **`your-username.github.io`** (replace `your-username` with your GitHub handle). This naming gives you a clean URL: `https://your-username.github.io`.
2. Add `index.html` and `style.css` to the repo root.
3. Commit and push.
4. Go to **Settings → Pages**, set source to `main` branch, root folder. Save.
5. Visit `https://your-username.github.io` after a minute or two.

Alternatively, you can use any repo name and deploy from a `/docs` folder or `gh-pages` branch — your URL will then be `https://your-username.github.io/repo-name`.

## What to customize

Search-and-replace these placeholders in `index.html`:

- `Soomin [Last Name]` → your full name
- `your-username` → your GitHub handle (appears in GitHub + footer links)
- `your-handle` → your LinkedIn handle
- `you@example.com` → your email
- `resume.pdf` → drop a `resume.pdf` in the repo root, or remove the link
- `[Undergraduate Institution]` and `[Field]` → your prior degree
- `[Project Three]` → replace with a real project (or delete the card)

Add or remove keyword pills freely — they're just `<span class="pill">...</span>` elements.

## Design notes

- **Typography**: Fraunces (display serif, with optical sizing) + JetBrains Mono (technical accents)
- **Palette**: warm off-white background, near-black ink, burnt-orange accent used sparingly
- **Pill variants**: default (outlined), `pill-accent` (filled, for research), `pill-ghost` (dashed, for "currently learning"), `pill-sm` (compact, for project tags)

## File structure

```
your-username.github.io/
├── index.html
├── style.css
├── resume.pdf      (optional)
└── README.md       (optional)
```

No build step. No dependencies. Just two files.
