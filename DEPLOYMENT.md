# Deployment-ready Ingenero website

Upload the CONTENTS of this folder to a static web host. index.html must be at the web root. Preserve directory names and capitalization. All fonts, icons, JavaScript, images, brochures, demo videos and the requested corporate video are included locally. The intentionally external links are Outlook compose and the existing company/social destinations.

For local review, run python preview_website.py and open http://127.0.0.1:8773/index.html. Stop another server using that port first. The server supports HTTP byte ranges for video seeking.

Configure the production host to serve .mp4 as video/mp4, .woff2 as font/woff2, .json as application/json and .webp as image/webp. Enable HTTPS and gzip/Brotli for HTML, JavaScript, CSS and JSON. Let the host support byte ranges for media. Cache media/assets; use revalidation for index.html.

Email actions open Outlook on the Web with solutions@ingenero.ai pre-filled. The contact form places the entered details in a draft; the visitor reviews and sends it. Outlook sign-in may be required. No form data is automatically sent and the page no longer shows a false sent confirmation. No mail server or historian backend was added. Existing demonstration widgets retain their original demonstration behavior.

All displayed website content was preserved. The corporate video source changed as requested. The solar view retains every agent/capability name and exact orbital lap periods. Desktop, tablet and phone layouts and the primary navigation were checked. Static local asset references and inline handler targets were validated. These checks cover the static front end; production host and authenticated Outlook behavior must be verified in the deployment environment.

Canonical editable source: the parent Marketing Brochure folder. Source maintenance files live in site-theme, ingenerox-page and ingenerox360ai. Backups, editable source snapshots and unrelated marketing material are excluded from this deployment package.
