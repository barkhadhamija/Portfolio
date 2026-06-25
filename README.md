# The Franklin — Your Portfolio

A newspaper-style personal portfolio inspired by the Chilton Franklin.

---

## How to use this file

Open `index.html` in any browser — no build tools, no installs needed. It's a single file.

---

## What to fill in

Search for these placeholders in `index.html` and replace them with your own info:

| Placeholder | What to put |
|---|---|
| `Your Name` | Your actual name |
| `Your City, Country` | Where you're based |
| `your@email.com` | Your email address |
| `yourhandle` | Your LinkedIn / Instagram handle |
| `Designer & Developer` | Your actual role |
| `20XX` | The year you started |
| `Project One / Two...` | Your real project names and descriptions |

---

## How to add your photo (About section)

1. Find this comment in the HTML:
   ```
   <!-- Replace with your own <img src="your-photo.jpg" ... /> -->
   ```
2. Put your photo file in the same folder as `index.html`
3. Replace the `<svg>` placeholder block with:
   ```html
   <img src="your-photo.jpg" alt="Your Name" style="width:100%;height:100%;object-fit:cover;" />
   ```

---

## How to add Gilmore Girls cutouts

For each quote block, find the comment like:
```
<!-- Replace with: <img src="lorelai-cutout.png" ... /> -->
```

Then:
1. Find a still from Gilmore Girls you like
2. Remove the background using **remove.bg** (free, fast)
3. Save as a PNG (keep the transparent background)
4. Put the PNG in the same folder
5. Replace the `<svg>` placeholder with:
   ```html
   <img src="lorelai-cutout.png" alt="Lorelai Gilmore" style="width:100%;height:100%;object-fit:cover;" />
   ```

Tips for good cutouts:
- Pick candid moments over posed ones (Lorelai mid-laugh holding coffee, Rory looking down at a book)
- Portrait orientation works best (taller than wide)
- The slight rotation is already applied via CSS — you don't need to rotate the image itself

---

## How to update the ticker

Find the `.ticker-inner` `<span>` near the top and change any of the text between the `·` separators. Update "COFFEE COUNT: 4" daily if you want to commit to the bit.

---

## How to update "On the Reporter's Desk"

Find the `CURRENTLY READING / DRINKING / WATCHING` section near the bottom and update the values as your taste changes.

---

## Fonts used

All loaded from Google Fonts (no install needed):
- **UnifrakturMaguntia** — masthead blackletter
- **Playfair Display** — headlines and project titles
- **EB Garamond** — body copy and captions

---

## Hosting

To put this online for free:
- **Netlify Drop** — drag the entire folder to netlify.com/drop
- **GitHub Pages** — push to a repo and enable Pages in settings
- **Vercel** — drag and drop the folder at vercel.com

---

*Made with too much coffee.*
