# Vasuki Eye Care — Official Website

Static one-page website for **Vasuki Eye Care — Dr. Sunitha P (MBBS, DOMS, FAEH, Glaucoma)**
Cataract & Glaucoma Surgeon — 8th Main Road, Koramangala, Bengaluru — 560034
Phone: 86605 61268 · Email: vasukieyecare@gmail.com · Timings: 11:30 AM – 7:00 PM

---

## What's inside

| File | Purpose |
|---|---|
| `index.html` | The entire website (HTML + CSS + JavaScript in one file, ~48 KB) |
| `images/` | 5 clinic photos as optimized JPEGs (~334 KB total) |
| `README.md` | This guide |

No frameworks, no build tools, no external JavaScript — just open and it works.

---

## 1. Preview it on your computer

Double-click **`index.html`** — it opens in your browser.

> Everything (photos, layout, buttons, WhatsApp, calling) works **offline**.
> Only two things need internet: the Google Map and the Google Fonts styling.

---

## 2. Upload to GitHub (free hosting)

### Step A — create the repository
1. Sign in to <https://github.com> → click **+** → **New repository**
2. Repository name: `vasuki-eye-care` (or any name)
3. Select **Public** → click **Create repository**

### Step B — upload the files
1. On the empty repo page, click **"uploading a file"** (or **Add file** → **Upload files**)
2. Drag these from this folder into the browser:
   - `index.html`
   - the `images` folder
3. Commit the changes.

### Step C — turn on GitHub Pages
1. Go to **Settings** → **Pages**
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**
3. Set **Branch** to `main` and folder `/ (root)` → click **Save**
4. Wait ~1 minute. Your site is live at:
   `https://YOUR-USERNAME.github.io/vasuki-eye-care/`

---

## 3. Editing the content later

Everything is in `index.html`. Common edits:

| Change | Search for |
|---|---|
| Phone number | `86605 61268` and `+918660561268` |
| Timings | `11:30 AM` |
| Address | `Shri Ganga` |
| Opening paragraph | `Calm, unhurried eye care` |
| Reviews | `What our patients say` |
| Services | `Eye care services at` |

Save the file and refresh the browser to see the change.

---

## Notes for developers

- **Images**: the site uses `images/*.jpg` (optimized, ~334 KB total). The original
  full-size PNGs are intentionally not included — they were 3.8 MB and 11x larger
  with no visible benefit at web sizes.
- **Every `<img>` has explicit `width`/`height`** to prevent layout shift (CLS).
- **Accessibility**: skip link, keyboard-operable gallery lightbox with focus
  restore, visible focus rings, `prefers-reduced-motion` support, and all
  text/background colour pairs meet WCAG AA contrast.
- **SEO**: Open Graph and Twitter card tags, plus `MedicalClinic` JSON-LD
  structured data with opening hours and services.
