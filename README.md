# ✦ Hostel Choir App

A PWA (Progressive Web App) for managing the hostel choir's songs, lyrics, pitch, and Sunday planning.

## Live App
👉 **[Your GitHub Pages URL here once deployed]**

## How to Install on Android
1. Open the link above in **Chrome**
2. Tap the **"Add to Home Screen"** banner at the bottom
3. Or tap Chrome menu (⋮) → "Add to Home Screen"
4. The app icon will appear on your home screen

---

## For the Choir Leader

**Default passcode:** `choir2025`

To change the passcode:
1. Open `index.html`
2. Find this line near the bottom: `const LEADER_PASSCODE = "choir2025";`
3. Change `choir2025` to your new passcode
4. Save and push to GitHub

**What leaders can do:**
- Add new songs (title, category, pitch, lyrics)
- Mark songs as "Sung Today" (updates for everyone)
- Edit pitch of any song
- Delete songs
- Set the Sunday planner (visible to all members)

**What members can do:**
- Browse and search all songs
- View full lyrics
- Copy lyrics as formatted text (for WhatsApp)
- Copy the Sunday plan for WhatsApp
- View song suggestions

---

## Tech Stack
- **Frontend:** Vanilla HTML/CSS/JS — no build tools needed
- **Database:** Firebase Firestore (real-time sync)
- **Hosting:** GitHub Pages (free)
- **Offline:** Service Worker caches the app shell

## Firebase
The app connects to the `hostel-choir` Firebase project.
- Firestore collections: `songs`, `shared/planner`
- Config is in `index.html` under `firebaseConfig`

---

## Handing Over to Juniors (Every Year)
1. Add them as collaborators on the GitHub repo (Settings → Collaborators)
2. Share the leader passcode with the new choir lead
3. That's it — they own it now

## Deploying Updates
```bash
# After making any changes:
git add .
git commit -m "describe your change"
git push
# GitHub Pages auto-deploys in ~60 seconds
```

---

*Built with love for the hostel choir. Pass it on.* 🎵
