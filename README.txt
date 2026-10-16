CYBERARCH PORTFOLIO HUB — WEBSITE PACKAGE

Files:
- index.html: upgraded portfolio website
- assets/background.mp4: extracted fullscreen/video-window background from the previously supplied CYBERARCH video-background build

DEPLOY WITH CLOUDFLARE PAGES (FREE STATIC HOSTING)
1. Extract this ZIP on your computer or phone.
2. In Cloudflare Dashboard, open Workers & Pages.
3. Choose Create application > Pages (or Create project, depending on dashboard layout).
4. Choose Direct Upload / Upload assets.
5. Upload the extracted folder contents so index.html is at the root and assets/background.mp4 is inside the assets folder.
6. Deploy. Cloudflare will show the live pages.dev URL.

IMPORTANT
- Keep the folder structure unchanged.
- This creates a Pages deployment and may have a different URL from your existing workers.dev site. To replace the existing workers.dev deployment, the existing Worker/project must be updated in the Cloudflare account.
- This is a static front-end. Portfolio entries are stored in each visitor's browser localStorage; they are not automatically shared or synchronized across devices.
- Video autoplay depends on browser policies and available bandwidth.
