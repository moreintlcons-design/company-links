# Company QR Landing Page Kit

This folder contains a stylish, mobile-first landing page with buttons to your company links
(Facebook, Instagram, LinkedIn, Website, Location, and Company Profile PDF), plus printable QR images.

## How to use
1) Replace the placeholders in `index.html`:
   - Company name
   - Button links (Facebook/Instagram/LinkedIn/Website/Maps)
   - The footer "QR target" text (this is the **final hosted URL** you will point the QR code to)
2) Put your real PDF at `assets/company-profile.pdf` (same filename to keep the link stable).
3) Host this folder (for free) using GitHub Pages / Netlify / Vercel.
4) Update and regenerate the QR code (see below) to point at your hosted URL.
5) Print the QR (SVG preferred for high quality) for your car sticker.

## Recommended QR size (car sticker)
- Rule of thumb: minimum size ≈ scanning distance / 10.
  - For 1 m distance → ~10 cm wide
  - For 2 m distance → ~20 cm wide
- Keep a white quiet zone around the code (≥ 4 modules).

## Regenerating the QR
- Edit `qr/url.txt` to your final hosted URL.
- Use the provided `qr/qr.png` or `qr/qr.svg` if already correct, or regenerate with a QR tool of your choice.
