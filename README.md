
# Glidepath Solutions — Netlify + CMS site

## Deploy
- Drag this folder into Netlify (Add new site → Deploy manually).
- Visit `/admin/` to access the CMS.

## Enable CMS (one-time)
1. In Netlify site settings: **Identity → Enable Identity**.
2. Click **Invite users** and invite your own email address.
3. In **Identity → Services**, enable **Git Gateway**.
4. Log in at `/admin/` using Netlify Identity; edit **Updates / Blog → Posts List**.
   - Add cards with Title, Summary, Date and the LinkedIn URL (or any URL).

## Domain
Point Squarespace domain DNS to Netlify:
- A records: `75.2.60.5` and `99.83.229.19`
- CNAME `www` → your-site-name.netlify.app

## Forms
- Contact form name: `contact` with redirect to `/thank-you.html`.
- In Netlify → **Forms → contact → Notifications**, add an email to `admin@glidepathsolutions.co.uk`.
