# Bloodlines Ink — Website

Tattoo studio website for Bloodlines Ink, Shannon, Co. Clare, Ireland.

## Project Structure

```
bloodlines-ink/
├── index.html          ← Main page (edit this for content)
├── css/
│   └── style.css       ← All styles
├── js/
│   └── main.js         ← Scroll effects + gallery lightbox
└── images/
    ├── logo.jpg         ← Studio logo
    ├── tattoo1.jpg      ← Gallery photo (featured)
    └── tattoo2.jpg      ← Add more photos here...
```

## How to add photos to the gallery

1. Drop your `.jpg` photo into the `/images/` folder
2. Open `index.html` in Cursor
3. Find the `<!-- GALLERY -->` section
4. Copy one of the commented-out blocks and update the filename:

```html
<div class="g-item">
  <img src="images/tattoo2.jpg" alt="Tattoo work — Bloodlines Ink">
  <div class="g-overlay"><span class="g-overlay-text">Bloodlines Ink</span></div>
</div>
```

5. Save and refresh the browser — done!

## How to run locally

Just open `index.html` in your browser. Or in Cursor:
- Install the **Live Server** extension
- Right-click `index.html` → **Open with Live Server**

## How to deploy (Netlify — free)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire `bloodlines-ink/` folder into the browser
3. Done — you get a live URL instantly

To connect your domain `bloodlines.ink`:
- In Netlify → Site Settings → Domain Management → Add custom domain

## Instagram DM Link

All booking buttons use: `https://ig.me/m/bloodlines.ink`

To change the Instagram handle, search for `bloodlines.ink` in `index.html` and replace.
