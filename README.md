# YAW'S YAMS AND CROPS EXPO. - Website

A modern, responsive website for YAW'S YAMS AND CROPS EXPO., a Ghanaian agricultural export company specializing in premium yams and crops.

## 🚀 Quick Deploy to Netlify

This website is ready for deployment on Netlify. You can deploy it in several ways:

### Option 1: Drag & Drop Deployment
1. Zip the entire project folder
2. Go to [Netlify](https://app.netlify.com)
3. Drag and drop the zip file to deploy instantly

### Option 2: Git-based Deployment
1. Push this repository to GitHub
2. Connect your GitHub account to Netlify
3. Select this repository for automatic deployments

### Option 3: Netlify CLI
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy from project directory
netlify deploy --prod
```

## 📁 Project Structure

```
├── index.html          # Homepage
├── products.html       # Products page
├── contact.html        # Contact page
├── 404.html           # Custom 404 page
├── styles/
│   └── global.css     # Main stylesheet
├── images/            # Image assets
│   ├── hero/         # Hero section images
│   ├── yams/         # Yam product images
│   ├── maize/        # Maize product images
│   ├── groundnuts/   # Groundnut images
│   ├── beans/        # Bean images
│   └── agushi/       # Agushi images
├── catalog/           # Product catalog directory
├── netlify.toml       # Netlify configuration
├── _redirects        # Netlify redirects
├── robots.txt        # SEO robots file
└── sitemap.xml       # SEO sitemap
```

## 🔧 Features

- **Responsive Design**: Mobile-first, works on all devices
- **SEO Optimized**: Meta tags, sitemap, robots.txt
- **Performance**: Optimized images and caching headers
- **Netlify Ready**: Pre-configured with netlify.toml and _redirects
- **Social Media**: Open Graph and Twitter card meta tags
- **Accessibility**: Semantic HTML and ARIA labels

## 🛠 Development

This is a static website built with vanilla HTML, CSS, and JavaScript. No build process required.

### Local Development
Simply open `index.html` in your browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Using VS Code Live Server extension
# Right-click index.html > "Open with Live Server"
```

## 📞 Contact Information

- **Email**: emmanuelagyei1213@gmail.com
- **Phone**: +233 595108757
- **WhatsApp**: +233 595108757

## 🌟 Products

- **Yams**: Premium Puna Yams and varieties
- **Groundnuts**: Organic, cleaned and shelled
- **Beans**: Quality cowpea beans
- **Maize**: Fresh maize, white and yellow varieties
- **Agushi**: Quality agushi seeds

## 📝 License

© 2024 YAW'S YAMS AND CROPS EXPO. All rights reserved.

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