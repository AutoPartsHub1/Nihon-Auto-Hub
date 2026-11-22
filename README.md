# Nihon Auto Hub demo website

Responsive Japanese used-auto-parts importing business website built with plain HTML, CSS and JavaScript.

## Files
- `index.html` — store/catalog and inquiry form
- `login.html` — demo login/profile
- `signup.html` — demo registration
- `style.css` — responsive design
- `script.js` — catalog, filters, demo cart, WhatsApp inquiry and demo account UI

## Customize before publishing
1. In `script.js`, replace `WHATSAPP_NUMBER` with your WhatsApp number in international format, digits only (no plus sign).
2. Replace demo products, prices, categories, part numbers and image URLs in `demoProducts` and `categoryData`.
3. Update phone, email, social links, business hours and address in `index.html`.
4. Replace sample/demo labels and inventory content as needed. Demo prices are not quotations.


## Demo account security
Account forms are UI demonstrations only. They do not securely authenticate users and should not be used with real passwords. A production account system needs a backend or authentication service (such as Firebase Authentication or Supabase Auth), secure password handling, account recovery and server-side access controls. This static site does not save passwords.


## GitHub Pages deployment
1. Create a GitHub repository (for example `nihon-auto-hub`).
2. Upload all files in this folder to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
5. Wait for deployment and open the URL GitHub Pages displays, usually `https://YOUR-USERNAME.github.io/nihon-auto-hub/`.

No build step is required.
