# Parsa WG Website

A polished one-page personal website for WG applications in Darmstadt.

## What to edit first

Open `index.html` in any text editor and replace:

- `01.10.2026` with your real move-in date
- `€650 warm` with your actual maximum budget
- `your.email@example.com` with your email
- `491234567890` in the WhatsApp link with your real number in international format
- Any text that does not sound like you
- The study / duration / pet / smoking details if needed

## Add your photos

The current version intentionally uses beautiful styled placeholders so the page works immediately.

For a real photo, replace a placeholder like:

```html
<div class="photo-placeholder">
  ...
</div>
```

with:

```html
<img src="images/profile.jpg" alt="Parsa" />
```

Then put the image inside an `images` folder.

Recommended photos:
1. Main portrait: natural, clear, friendly
2. Travel / outdoors photo
3. Hobby or gym / coffee / cooking photo
4. One social photo, but not a giant group where nobody knows which person you are

## Publishing

### Easiest: Netlify
1. Go to Netlify.
2. Create a free account.
3. Drag the whole `parsa-wg-website` folder into the deploy area.
4. Netlify gives you a public link immediately.

### GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html`, `styles.css`, and `script.js`.
3. In repository Settings → Pages, deploy from the main branch.
4. GitHub gives you a public URL.

## Important privacy note

Do **not** put passport scans, residence permits, bank statements, signatures, exact financial balances, or similar documents directly on the public website.

The wording “documents available upon request” is intentional.

## Design notes

The site is intentionally:
- friendly rather than corporate
- elegant but not flashy
- mobile responsive
- fast
- framework-free
- easy to edit

You do not need React, Next.js, or any build step.
