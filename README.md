# তারেক একাডেমি (Tarek Academy)

বাংলাভাষীদের জন্য স্কিল শেখা ও ফ্রিল্যান্সিং প্রস্তুতির একটি responsive, static website। এটি GitHub Pages-এ বিনা খরচে প্রকাশ করা যায়।

## এখন যা আছে

- বাংলায় responsive landing page এবং SEO title, description, Open Graph ও structured data
- কোর্স কার্ড, ক্যাটাগরি filter এবং সার্চ
- কাজের প্রস্তুতির নমুনা তালিকা
- সাইন-আপ ফর্ম; ডেমো তথ্য কেবল ব্যবহারকারীর নিজস্ব ব্রাউজারের `localStorage`-এ থাকে
- কোনো external library, paid service বা build step লাগবে না

## স্থানীয়ভাবে চালান

`index.html` ফাইলটি ব্রাউজারে খুলুন। অথবা repository root-এ একটি static HTTP server চালান।

## GitHub Pages-এ বিনা খরচে প্রকাশ

1. GitHub-এ এই repository খুলুন।
2. **Settings → Pages**-এ যান।
3. **Deploy from a branch** বেছে নিয়ে branch `main` এবং folder `/(root)` নির্বাচন করে Save করুন।
4. Pages-এর প্রকাশিত URL (সাধারণত `https://mh6778878-crypto.github.io/Mohammad-Tarek/`) খুলে পরীক্ষা করুন। প্রথম প্রকাশে কিছু সময় লাগতে পারে।

## Google Search-এ পাওয়ার জন্য

GitHub Pages-এ প্রকাশিত URL সক্রিয় হওয়ার পর সেটি Google Search Console-এ যোগ করে ownership verify করুন, তারপর URL Inspection দিয়ে homepage indexing-এর জন্য request করুন। Google কখন বা আদৌ index করবে তার নিশ্চয়তা নেই; সাইটটি public এবং crawl করার উপযোগী থাকতে হবে। Pages-এর URL পেলে `index.html`-এ canonical URL, Open Graph URL এবং `sitemap.xml`-এ সঠিক URL যোগ করা ভালো।

## বাস্তব পেমেন্ট/অ্যাকাউন্ট সম্পর্কে

এটি এখন frontend-only শিক্ষামূলক MVP। এখানে বাস্তব user authentication, server/database, client marketplace, টাকা জমা/উত্তোলন, wallet, বা payment integration নেই। বাস্তব টাকা বা ব্যবহারকারীর ব্যক্তিগত তথ্য নেওয়ার আগে নিরাপদ backend, পরিচয়/লেনদেন যাচাই, পেমেন্ট provider-এর অনুমোদিত API, privacy policy, এবং প্রযোজ্য আইনগত পর্যালোচনা দরকার। এই ডেমো কখনও বাস্তব balance বা আয়ের প্রতিশ্রুতি দেয় না।
