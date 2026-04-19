# Om Nath Sarraf — Heritage Jewellers

Official website for **Om Nath Sarraf**, wholesale & retail jewellers from Rudhauli Bazaar, Basti, Uttar Pradesh.

🔗 **Live site:** https://YOUR-USERNAME.github.io/om-nath-sarraf/
📷 **Instagram:** [@omnathsarraf_07.09](https://www.instagram.com/omnathsarraf_07.09/)

## About

Single-page website featuring:
- Bridal, Polki, Gold and Silver collections
- Heritage story & craftsmanship section
- Instagram feed integration
- Store locator & contact details
- Fully responsive (mobile, tablet, desktop)

## Tech

Pure HTML + CSS + a tiny bit of vanilla JS. No frameworks, no build step. Just open `index.html` in a browser.

## Updating product photos

Each placeholder image area in `index.html` is marked with a comment like:

```html
<!-- DROP IN: Replace this with an <img src="..."> -->
```

To use real photos:
1. Add your image files to an `images/` folder in this repo
2. Find each `DROP IN` comment in `index.html`
3. Replace the placeholder `<svg>...</svg>` block with `<img src="images/your-photo.jpg" alt="Description" />`

## Updating contact info

Search and replace these placeholders in `index.html`:
- `+91 9XXXX XXXXX` → real phone number
- `hello@omnathsarraf.com` → real email
- `1962` → actual founding year if different
