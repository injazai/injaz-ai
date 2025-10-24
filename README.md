# Injaz AI Landing Site

A modern, responsive landing page for Injaz AI—a Kuwait-based agency delivering custom chatbots and automation services for restaurants, spas, salons, and clinics. The project also includes dedicated privacy and data-deletion policy pages styled consistently with the main site.

## Project structure

```
├── index.html          # Primary marketing page
├── privacy.html        # Privacy Policy (October 2025)
├── data-deletion.html  # Data Deletion Policy (October 2025)
└── styles.css          # Global styles shared by all pages
```

All pages reference `styles.css` with relative paths, so keep the files in the same directory (or update the paths if you reorganize).

## Development

Open any of the HTML files directly in your browser to preview the site. Because the layout is fully static, no build tools or package managers are required.

- Update copy or imagery by editing the relevant HTML sections.
- Adjust colors, typography, or responsive behavior in `styles.css`.

## Deployment

The site is a static bundle that can be uploaded to any web host. To deploy on Hostinger using hPanel:

1. Compress the four project files (or upload them individually).
2. In hPanel, open **Files → File Manager** and go to the `public_html` directory.
3. Upload the files (or extract the archive) so that `index.html`, `privacy.html`, `data-deletion.html`, and `styles.css` sit directly inside `public_html`.
4. Visit your domain to confirm the landing page loads and that the footer links open both policy documents.

### Optional: FTP deployment

1. Create or note your FTP credentials under **Files → FTP Accounts** in hPanel.
2. Connect using an FTP client such as FileZilla (Host, Username, Password, Port 21).
3. Transfer the same file bundle into `/public_html/`, preserving the folder structure.

## Contact & socials

The footer links use `hello@injaz.ai`, `instagram.com/injazai`, and `tiktok.com/@injazai`. Update these values in the HTML if your contact information changes.

## License

All rights reserved © Injaz AI. Update this section if you plan to release the code under a specific license.
