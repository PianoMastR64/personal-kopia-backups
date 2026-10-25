# Personal Kopia Backups information website

Static homepage and privacy policy for a personal Kopia/rclone Google Drive OAuth application. No build, dependencies, scripts, forms, or credentials are required.

## Publish to GitHub Pages

Use a dedicated public repository named `PianoMastR64/personal-kopia-backups`. Publish only this directory's files, not the containing Computer Config workspace. In repository Settings → Pages, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then Save.

Published URLs (homepage and privacy policy verified in Chrome on October 25, 2026):

- Homepage: `https://pianomastr64.github.io/personal-kopia-backups/`
- Privacy policy: `https://pianomastr64.github.io/personal-kopia-backups/privacy.html`
- Google OAuth authorized domain: `pianomastr64.github.io`

Add the live URLs to Google Auth Platform → Branding for the existing rclone project. Use the owner's support email in Google's form; it is not published in these files. Keep the app name consistent with this website. Google may request domain ownership verification through Search Console. GitHub Pages hosting alone does not establish Google verification.

After saving Branding, return to Audience and publish the OAuth app. Then reconnect rclone to obtain fresh authorization outside Testing status. These are separate steps from publishing the website.

## Maintenance

- `index.html`: purpose, operations, and contact.
- `privacy.html`: data practices, retention, revocation, and hosting disclosure.
- `styles.css`: shared responsive styling.
- `.nojekyll`: publish ordinary static files without Jekyll processing.

Keep the policy accurate when the backup setup changes. Never add rclone configuration, OAuth credentials, logs, repository data, or private contact details to this public repository. Contact links use public GitHub issues.
