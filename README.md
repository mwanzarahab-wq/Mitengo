# Mitengo (PWA)
Deploy: put this folder on Vercel (vercel CLI inside the folder, or import the Git repo). No build step.
Backend (optional, for live prices, scouts, receipts): run supabase.sql in Supabase, then put URL + anon key in config.js and redeploy.
Make a scout: sign up in the app, then run the update statement at the bottom of supabase.sql.
Install: open the site on your phone, tap "Install app" (Android/Chrome) or Share > Add to Home Screen (iPhone).
