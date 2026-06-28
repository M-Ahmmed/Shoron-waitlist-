Shoron waitlist — ULTIMATE deploy-ready build

What is included:
- Complete static waitlist website with index.html at the root.
- Shoron favicon package fully attached: favicon.ico, 16x16, 32x32, Apple Touch icon, Android Chrome icons, and site.webmanifest.
- Google Analytics 4 connected with Measurement ID: G-1YSCP8N91V.
- Formspree waitlist endpoint preserved: https://formspree.io/f/xzdlrlle.
- Requested Bangla/English copy updates implemented.
- Heavy inline images moved to /assets and optimized for faster loading.
- DNS-prefetch/preconnect hints added for Google Analytics and Formspree.
- Vercel cache headers added for assets, favicons, and manifest.
- Formspree submit timeout added so bad Wi-Fi does not keep the form stuck forever.
- Safer local backup behavior added so browser storage errors do not break signup.

Deploy to Vercel:
1. Upload this zip/folder to Vercel as the project root.
2. Vercel should serve index.html automatically.
3. After deployment, open the live site and hard refresh once.

Verify after deployment:
1. Open the live site.
2. Press Ctrl+U and search for: G-1YSCP8N91V
3. Open Google Analytics → Reports → Realtime.
4. Submit a test waitlist form.
5. Check Formspree inbox and GA4 event: waitlist_signup

Important favicon note:
Browsers cache favicons aggressively. If the favicon does not update instantly, use Incognito or hard refresh with Ctrl+Shift+R.
