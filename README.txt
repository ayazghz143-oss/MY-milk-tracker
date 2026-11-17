MY MILK TRACKER — INSTALLATION GUIDE

Your app is ready. It tracks:
- Received / not received each day
- Quantity in litres and extra quantity
- Monthly litres and estimated bill
- Rate per litre (default ₹52) and regular quantity (default 1 L)
- Month navigation and CSV export
- Offline use after first successful load
- Records saved locally in this browser on this phone

IMPORTANT:
A PWA must be served from HTTPS (or localhost) to be installable and use offline caching.
Opening index.html directly from a ZIP/file manager will let you preview it, but will NOT install it as a PWA.

EASIEST FREE METHOD — GitHub Pages:
1. On your phone or computer, create/sign in to a GitHub account.
2. Create a new public repository, e.g. milk-tracker.
3. Upload ALL files from this folder to the repository's main/root folder.
4. In the repository, open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select branch "main" and folder "/ (root)", then Save.
7. Wait for GitHub Pages to publish the site. Open the published HTTPS URL in Chrome on Android.
8. In Chrome, tap ⋮ > Add to Home screen or Install app.
9. Open the installed app. Your entries will be saved on that phone/browser.

BACKUP:
Use Export CSV each month. Browser storage can be lost if browser data is cleared or the app is removed.

HOW TO RECORD:
- Tap a date.
- Tap Received or Not received.
- For received milk, enter total quantity for that day (e.g. 1.5 L if you got 1 L regular + 0.5 L extra).
- Tap Save this day's record.
- Monthly bill is quantity × rate per litre.
