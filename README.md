# Kāsu website

Four static pages. No build step, no server code.

- index.html   home page (scroll animations use GSAP + ScrollTrigger + Lenis from public CDNs)
- support.html support and FAQ
- privacy.html privacy policy (app stores ask for this URL)
- terms.html   terms of use

## Deploy
Drag this folder onto Netlify Drop or Vercel, or push it to a GitHub repo and turn on GitHub Pages.
Point your domain at it. Use https://yourdomain/privacy.html and https://yourdomain/support.html
in App Store Connect and the Play Console.

## Fill in before launch
Replace [YOURDOMAIN] in support.html, privacy.html and terms.html with your real email domain.
Swap the two download buttons' links (https://apps.apple.com/ and https://play.google.com/store)
for the real store listings.
