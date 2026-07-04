# Michael Bulkaam Shikpan - Academic Website

This folder contains a ready-to-upload static academic website for GitHub Pages.

## What is included

- `index.html` - the main website page.
- `assets/styles.css` - the website design and layout.
- `assets/script.js` - small mobile-menu and footer-year script.
- `assets/Michael_Bulkaam_Shikpan_CV.pdf` - the CV PDF used by the website.
- `assets/favicon.svg` - the browser icon.
- `.nojekyll` - tells GitHub Pages to serve the files as plain static files.

## Publish on GitHub Pages

1. Create or sign in to your GitHub account.
2. Create a new repository named exactly: `YOUR-GITHUB-USERNAME.github.io`.
3. Upload all files and folders from this package into the repository root.
4. Commit the upload.
5. Go to **Settings > Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select the `main` branch and `/ (root)`, then save.
8. Your site will be available at: `https://YOUR-GITHUB-USERNAME.github.io/`.

## Update the website

### Update the CV PDF

Replace this file with your new CV, keeping the same filename:

`assets/Michael_Bulkaam_Shikpan_CV.pdf`

Then commit the change. The CV buttons and embedded viewer will continue to work.

### Update text on the homepage

Open `index.html`, use GitHub's pencil/edit button, make changes, and commit.

Recommended sections to update regularly:

- Hero paragraph near the top.
- Research interests.
- Publications and projects.
- Teaching and mentorship.
- Fieldwork.
- Contact links.

### Add a photo later

The site currently uses an initials card. To add a photo later:

1. Upload a professional photo to `assets/`, for example `assets/profile.jpg`.
2. In `index.html`, replace the `portrait-placeholder` block with:

```html
<img class="profile-photo" src="assets/profile.jpg" alt="Portrait of Michael Bulkaam Shikpan">
```

3. Add this to `assets/styles.css` if needed:

```css
.profile-photo {
  width: 100%;
  height: 230px;
  object-fit: cover;
  border-radius: 18px;
}
```

## Review checklist

After publishing, check the site on desktop and phone. Confirm that:

- The CV button opens the PDF.
- The embedded PDF appears in the CV section.
- Email links open your email app.
- The website text is accurate and current.
- No private phone number, address, student number, or sensitive personal data appears online.
