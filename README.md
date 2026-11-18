# Daily cards — standalone iPhone app

This folder is a complete offline web app. It holds no personal data; your cards
live only on your phone after you restore your backup file.

## 1. Put the folder online (once)
Any static host works. Two free options:
- **Netlify Drop:** sign in at app.netlify.com, open "Drop", drag this whole folder in. You get an https address.
- **GitHub Pages:** create a repository, upload these files, then Settings → Pages → deploy from the main branch.

## 2. Install on the iPhone
1. Open the https address in **Safari**.
2. Tap Share → **Add to Home Screen**.
3. Open Daily cards **from the Home Screen icon** (not from Safari).

## 3. Restore your cards
1. Save `daily-cards-backup-2026-11-18.json` to Files (AirDrop, iCloud Drive or email).
2. In the Home Screen app, tap **Choose backup file** and pick it.

Do step 3 inside the Home Screen app: iOS keeps its storage separate from Safari's.

## Keep a backup
Settings → Export backup opens the share sheet; save the file to Files or iCloud Drive.
Do this every few weeks, and before deleting the app or changing phones.
