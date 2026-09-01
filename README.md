# DC Field Deployment Kit — Interactive Checklist

Live app: **https://jwineland.github.io/Field_toolkits/**

Interactive checklist for the Sourcecode / Thinkmate DC field deployment kit. Select a toolkit owner, categorize items, add notes, filter by status, and export to CSV. Each owner has independent statuses and comments while sharing the common material catalog.

## Usage

### View only
Open the live URL. No login required. Categories and notes are saved in your browser (localStorage).

### User profiles

Use the **Toolkit owner** menu to switch between Joel and Chris B. Chris can start with an empty profile or choose **Copy Joel's toolkit**, then customize statuses and notes without changing Joel's profile.

### Save shared state (team)
1. Select the correct toolkit owner
2. Create a GitHub Personal Access Token at https://github.com/settings/tokens with **repo** scope
3. Paste it into the token field at the top of the app and click Connect
4. Click **Save to GitHub** — changes write to `state.json` in this repo and are visible to all users on next load

### Adding or editing items
Edit `data.json` directly in this repo. The app fetches it fresh on every load.

## Files

| File | Purpose |
|---|---|
| `index.html` | Single-page app — all UI and logic |
| `data.json` | Kit item definitions (source of truth) |
| `state.json` | Shared categorization state (auto-created on first save) |
| `README.md` | This file |

## Enabling GitHub Pages

1. Go to **Settings → Pages** in this repo
2. Source: **Deploy from a branch**
3. Branch: **main** · Folder: **/ (root)**
4. Save — live in ~60 seconds

## Item tiers

| Tier | Meaning |
|---|---|
| Core | Always in the kit |
| Near-core | Usually included |
| Selective | Site/job dependent |
| Overflow | Spare/backup supply |
| Deferred | Future purchase |
