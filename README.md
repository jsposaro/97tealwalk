# 97TealWalk.com landing page

Static website ready for GitHub Pages deployment.

## Files
- `index.html` — landing page
- `styles.css` — styling
- `assets/location-context.jpg` — Google Earth wide/context image provided by owner
- `assets/location-close.jpg` — Google Earth parcel close-up image provided by owner
- `assets/survey-redacted.jpg` — survey preview with ownership/name area redacted
- `assets/deer-motif.png` — deer motif used for branding/watermark

## Form setup
The inquiry form is built for Formspree. To activate:

1. Create a free Formspree form.
2. Set the destination email to `jsposaro@gmail.com`.
3. In Formspree settings, set the email subject to `97 Teal Walk Inquiry` if desired.
4. Replace `FORM_ID_HERE` in `index.html` with your Formspree form ID.

Current placeholder:

```html
<form action="https://formspree.io/f/FORM_ID_HERE" method="POST">
```

## GitHub Pages deployment
1. Create a new GitHub repository, e.g. `97tealwalk`.
2. Upload all files/folders in this package to the repository root.
3. Go to Settings → Pages.
4. Set Source to `Deploy from a branch`, branch `main`, folder `/root`.
5. Add custom domain `97tealwalk.com` in Pages settings.
6. Update DNS at your domain registrar per GitHub Pages instructions.

## QR code
Once `https://97tealwalk.com` is live, generate the QR code from that final URL and test it before printing the sign.
