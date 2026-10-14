# Reed Taxi Privacy Policy website

A lightweight, static privacy-policy website for Reed Taxi.

## Files

```text
reed-taxi-privacy/
├── index.html
├── styles.css
└── README.md
```

`index.html` is the complete Privacy Policy. It uses only local HTML and CSS, with no JavaScript, forms, analytics, cookies, third-party fonts or external assets. No build command or package installation is required.

## Review before publishing

The public policy still needs the following business information:

1. A working public privacy contact, preferably a monitored email address, for privacy questions and deletion requests.
2. Confirmation of the business or legal name responsible for Reed Taxi, if it differs from the app name.
3. An approved account/data-deletion request and fulfillment process. The current app supports account deactivation, but deactivation is not complete data erasure.
4. Approved retention periods or clear retention criteria for account, trip, OTP, photo, log and backup data. The current service does not define a fixed deletion schedule.

Add only confirmed information. Do not invent a contact address, retention period, deletion promise or security guarantee.

## Manual Cloudflare Pages upload

No deployment has been performed.

After the items above are confirmed:

1. Open `index.html` locally and review the wording and narrow-screen layout.
2. Prepare a folder or ZIP containing `index.html` and `styles.css` at its root. Keep this README local.
3. In Cloudflare, open **Workers & Pages**, create a Pages application, and choose the direct upload option.
4. Upload the folder or ZIP and deploy it from the approved account.
5. Verify the returned HTTPS address in a private browser on desktop and mobile.

The expected root URL format is:

```text
https://<project-name>.pages.dev/
```

The site has no build step and no `dist` directory.

## Scope

This folder contains website files only. Publishing the page does not change the Reed Taxi mobile app, backend, database or Google Play configuration.
