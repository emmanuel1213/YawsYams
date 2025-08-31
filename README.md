# YamEx Ghana – Export Website

Professional, lightweight static site modeled on sections from Maphlix Trust's public layout for inspiration. Replace copy and images with your own.

## Edit your company details

- Open `index.html`, `products.html`, `gallery.html`, `contact.html` and update:
  - Company name (currently "YamEx Ghana")
  - Email, phone, addresses
  - Product lists and stats
  - Gallery image URLs
- Put your product catalog PDF at `catalog/YamEx-Catalog.pdf` and the "Download Catalog" buttons will work.

## Run locally

- Use a simple live server (VS Code Live Server or `npx serve`). On Cursor, right-click `index.html` and "Open with Live Server".

## Free hosting options

### A) GitHub Pages (free)
1. Create a GitHub repo (public). Name it anything, e.g. `yamex-site`.
2. Push the files in this folder to the repo root (`index.html` must be at root).
3. In GitHub, Settings → Pages → Source: Deploy from a branch → `main` / `/root`.
4. Wait 1–2 minutes. Your site will be at `https://<username>.github.io/yamex-site/`.

### B) Vercel (free)
1. Go to vercel.com and sign in with GitHub.
2. Import the repo, keep defaults. Framework preset: "Other" (static).
3. Deploy. Your site gets a `*.vercel.app` URL and custom domains are supported.

## SEO and metadata
- Update `<title>` and `<meta name="description">` in every page.
- Add your social preview: create `images/og.jpg` and later add Open Graph tags.

## Hero slider assets
- Place images in `images/hero/` as `01.jpg`, `02.jpg`, `03.jpg`, ...
- The first two are already reserved for your guide images.
- Optional: add a video clip as `clip01.mp4` and uncomment a video entry in the slider config in `index.html`.

## Structure
```
index.html
products.html
gallery.html
contact.html
styles/global.css
catalog/ (add your PDF here)
images/ (optional)
```

## Credits
- Layout inspiration: Maphlix Trust public website [`https://maphlixtrust.com/`](https://maphlixtrust.com/) 