# Mainstream Plumbing and Heating Website

Static, Netlify-ready one-page website.

## Files
- `index.html` — main website
- `styles.css` — full responsive styling and animation system
- `script.js` — mobile menu, sticky header, scroll reveal animations
- `thank-you.html` — Netlify form success page
- `netlify.toml` — Netlify settings
- `assets/` — optimized website images

## Netlify Deployment
1. Log in to Netlify.
2. Click **Add new site**.
3. Choose **Deploy manually**.
4. Drag the full `mainstream_site` folder into Netlify.
5. After it deploys, test the form and phone buttons.

## Domain Setup
Keep `mainstreamplumbingandheating.com` if possible.
In Netlify, go to **Domain management**, add the domain, and follow Netlify's DNS instructions.

## Contact Form Notifications
The form uses Netlify Forms. After first deployment and first test submission:
1. Go to Netlify dashboard.
2. Open the site.
3. Go to **Forms**.
4. Select `service-request`.
5. Add email notifications to `mainstream95@yahoo.com`.

## Notes
- The site avoids AC/HVAC language because the business does not do air conditioning.
- The main conversion goal is phone calls.
- The form is secondary.
- The animations respect reduced-motion accessibility settings.
