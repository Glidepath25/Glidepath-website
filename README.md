# Glidepath Solutions - Netlify + CMS site

## Deploy
- Drag this folder into Netlify using "Add new site" -> "Deploy manually".
- Visit `/admin/` to access the CMS.

## Enable CMS
1. In Netlify site settings, open **Identity** and enable Identity.
2. Invite your own email address under **Identity** -> **Invite users**.
3. In **Identity** -> **Services**, enable **Git Gateway**.
4. Log in at `/admin/`.

## Editable content
- **Homepage** -> **Homepage Content** controls the landing page hero, service cards, partnership section, testimonials, CTA band and contact copy.
- **Updates / Blog** -> **Posts List** controls the update cards and post pages.

## Domain
Point the Squarespace domain DNS to Netlify:
- A records: `75.2.60.5` and `99.83.229.19`
- CNAME `www` -> `your-site-name.netlify.app`

## Forms
- Contact form name: `contact` with redirect to `/thank-you.html`.
- In Netlify -> **Forms** -> **contact** -> **Notifications**, add the email recipient for submissions.
