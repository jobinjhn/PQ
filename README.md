# QR Photo Booth

This project is a mobile-first web photo booth.

## How it works
1. Guest scans a QR code.
2. A browser page opens.
3. The page requests camera permission.
4. The live camera appears with a photo-booth overlay.
5. Guest captures the photo.
6. The finished image is created with the frame embedded into it.
7. The Share button opens the phone's native share sheet where supported (Instagram, WhatsApp, Messages, etc.). If file sharing is unavailable, it downloads the image.

## Important
Camera access requires HTTPS on a deployed site (localhost is also acceptable for development).

## Customize
Open `index.html` and change:
- `YOUR EVENT`
- `#PHOTOBOOTH`
- `Make a memory ✦ Share the moment`
- frame color `#f5c451`
- typography and layout in the CSS

## Deployment
Upload `index.html` to any static HTTPS host such as GitHub Pages, Netlify, Vercel, or Cloudflare Pages.

After deployment, replace the QR URL with your public page URL.

## Final QR
The included QR currently points to:
https://your-photo-booth-site.example/

Replace it with your actual deployed URL after hosting.
