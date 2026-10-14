# Reed Taxi Privacy Policy website

A lightweight, static privacy-policy website for Reed Taxi.

## Files

```text
reed-taxi-privacy/
├── delete-account/
│   └── index.html
├── index.html
├── styles.css
└── README.md
```

`index.html` is the complete Privacy Policy. `delete-account/index.html` is the public account-deletion request page. Both use only local HTML and CSS, with no JavaScript, forms, analytics, cookies, third-party fonts or external assets. No build command or package installation is required.

## Public URLs

After deployment to the existing Cloudflare Pages project:

- Privacy Policy: `https://reed-taxi-privacy.pages.dev/`
- Account Deletion: `https://reed-taxi-privacy.pages.dev/delete-account/`
- Deletion email: `sriharicabs11@gmail.com`

The deletion page describes direct in-app deletion and email requests for users who cannot access the app. Email requests ask only for the registered name, registered mobile number and account type if known. Users are told never to send a password or OTP.

## Deployment

The static site is stored in GitHub and deployed through the existing Cloudflare Pages project. There is no build step and no `dist` directory.

After an approved commit is pushed to the connected GitHub branch, verify both public URLs in a private browser on desktop and mobile. No deployment was performed as part of this change.

## Scope

This folder contains website files only. Publishing the page does not change the Reed Taxi mobile app, backend, database or Google Play configuration.
