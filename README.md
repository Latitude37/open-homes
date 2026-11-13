# Latitude 37 | Open Homes

This repository hosts Latitude 37's **current featured open home** on GitHub Pages.

## Permanent address

Once published, the site remains at:

`https://YOUR-GITHUB-USERNAME.github.io/latitude37-open-homes/`

The address stays the same when you feature a different home.

## Publish for the first time

1. Create a **public** GitHub repository named `latitude37-open-homes`.
2. Upload `index.html` to the repository root and commit.
3. Open **Settings > Pages**.
4. Set **Source** to `Deploy from a branch`, **Branch** to `main`, and folder to `/(root)`. Save.
5. Wait for GitHub Pages to deploy and visit the URL above.

## Update the featured home each month

1. Prepare the new home's approved copy, photography, floor plans, viewing date and time, registration URL, and any award details.
2. Update `index.html` with the new property content and images. The current file embeds its images, so replacing the photos requires editing the HTML (not just uploading new image files).
3. Update the HTML `<title>` and `<meta name="description">` for the new property.
4. In GitHub, open `index.html`, click the pencil **Edit** icon, paste the updated HTML, then **Commit changes**. You can also upload a replacement `index.html` with the same filename.
5. Check the live page on desktop and mobile, including all buttons and registration links.

**Important:** The existing `index.html` currently showcases Black Rock. This is the first featured property, not a blank generic template. The permanent repository name and URL are universal. Each month the page content needs to be replaced.

## Monthly publishing checklist

- [ ] Property name and suburb
- [ ] Event date, session times and registration requirements
- [ ] Hero and supporting photography
- [ ] Home description and key features
- [ ] Floor plans, if approved
- [ ] Awards and factual claims verified for this property
- [ ] Registration link tested
- [ ] SEO title and description updated
- [ ] Desktop and mobile checked
- [ ] Old property details removed

## Practical note

If you want updates without editing HTML, a later version could use a small `home.json` content file or a content management system. This package deliberately keeps the existing self-contained website working on GitHub Pages without extra setup.
