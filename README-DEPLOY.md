# beranger events site: complete beginner guide to go live

Black artist design matching berangerofficial.com, full-screen video heroes, your Regensburg photos, German default with an EN/DE switch top right, and the Wedding page in white. No coding needed from you.

## What is already done
- Black theme, your white logo, uppercase nav, EN/DE toggle top right.
- Full-screen background video on the home, weddings and corporate pages.
- Your videos placed by category (see list below).
- Photos from your Regensburg shoot built in.
- Your bio, Spotify player, and social links (Spotify, Instagram, YouTube, TikTok, Facebook).
- Full SEO: titles, meta descriptions, hreflang DE/EN, sitemap, structured data.

## Videos currently placed (tell me to reorder anytime)
- Home hero (full screen): ymFusw7uiP8. Home gallery: IwLZoE0qibM, jK1_TJbrv_w, BzzIfacuHqQ (starts at 1:12:57).
- Weddings hero: 5kZCYFYgVL4. Plus: SPS8zSZEDfY.
- Corporate hero: CMwYzpM6YYc. Plus: ymFusw7uiP8.
- Private: jK1_TJbrv_w.
- I led the home with the first video you listed. If a different one is more visually striking, tell me the link and I will make it the hero in one edit.

## Preview it right now (no internet needed)
Double-click `index.html` in the `site` folder. It opens in your browser fully styled with photos and videos. (Menu links between pages only fully work once it is online, that is normal for a local preview.)

## Two small things only you can fill in
1. Contact form: go to formspree.io, sign up free, create a form, copy the form ID it gives you (looks like `xyzabcd`), and replace `YOUR_FORM_ID` in every .html file (the booking form now appears at the bottom of every page). A find-and-replace across files does all of them at once, or paste me the ID and I will do it. Now enquiries arrive in your inbox. If you want, I can do this replacement for you once you paste me the ID.
2. Domain: pick a name and buy it (step 1 below). Then tell me the domain and I will set it everywhere for you.

The logo is loaded from your Squarespace image link, so it just works. You can swap in a local logo file later if you ever leave Squarespace.

---

# GOING LIVE with GitHub + Vercel (step by step for a total beginner)

Total time about 20 minutes. Cost: about 10 to 12 euros per year for the domain. Hosting is free.

## STEP 1: buy a domain (about 10 euros per year)
1. Go to porkbun.com (or cloudflare.com or namecheap.com).
2. Search a name, for example `beranger-live.com` or `berangermusic.com`.
3. Buy it. That is the only thing you pay for.
4. Tell me the exact domain and I will bake it into every file (SEO needs the real domain), then re-send you the folder.

## STEP 2: create a free GitHub account
1. Go to github.com, click Sign up, make an account (free).
2. Click the plus icon (top right), choose "New repository".
3. Name it `beranger-events`. Leave it Public. Click "Create repository".

## STEP 3: upload the website files
1. On the new empty repository page, click the link "uploading an existing file".
2. Open the `site` folder on your computer. Select everything INSIDE it (the .html files, the `en` folder, the `assets` folder, styles.css, sitemap.xml, robots.txt). Drag them all onto the GitHub page.
   Important: upload the CONTENTS of the `site` folder, not the folder itself, so `index.html` sits at the top level.
3. Scroll down, click "Commit changes".

## STEP 4: deploy on Vercel (free)
1. Go to vercel.com, click Sign up, choose "Continue with GitHub", approve.
2. Click "Add New" then "Project".
3. Find `beranger-events` in the list, click Import.
4. Do not change any settings. Click Deploy.
5. Wait about a minute. You get a live link like `beranger-events.vercel.app`. Your site is live.

## STEP 5: connect your real domain
1. In Vercel, open your project, go to Settings, then Domains.
2. Type your domain (from Step 1), click Add, and follow the on-screen DNS instructions (Vercel tells you exactly what to paste at your domain provider). This takes a few minutes to activate.

## STEP 6: after it is live (this is the real SEO)
1. Create a free Google Business Profile: search "Google Business Profile", add "beranger, live music, Berlin". Local ranking depends heavily on this.
2. Add the site to Google Search Console (free), submit `sitemap.xml`.
3. Get listed on the agency and venue sites from your prospect spreadsheet. Those backlinks move you up more than anything on the page.

## Updating later
Any change: tell me what you want and I send you updated files, you drag them into GitHub the same way (it auto-redeploys via Vercel). You are never stuck.

## If you would rather I click through it with you
I can drive your browser (via the Claude in Chrome extension) and do the GitHub and Vercel steps live while you watch. Just say the word and make sure the Chrome extension is installed.

## Cost summary
Domain about 10 to 12 euros per year. Hosting free. Form free. Roughly 1 euro a month, versus 16 a month for a second Squarespace site.
