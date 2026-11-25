# DocTrack

Track pending company documents to collect, one task per company.

- Paste a pending-documents list; each company becomes a task
- Mark each document Pending / Received / Not received, with reason and review notes
- Project dashboard, "By document" view, and an all-projects pending list
- Export a styled Excel (.xlsx) report: Dashboard, All Documents, Pending
- Sign in with Gmail; projects are kept per account in the browser
- Backup / restore as JSON

## Run

Single file, no build. Open `index.html`, or deploy the folder to Netlify / GitHub Pages.

## One-click Google sign-in (optional)

1. Create an OAuth **Web** Client ID in Google Cloud Console → APIs & Services → Credentials.
2. Add your site URL (e.g. `https://doctrack.netlify.app`) under **Authorised JavaScript origins**.
3. Put the ID in `GOOGLE_CLIENT_ID` at the top of the script in `index.html`, or paste it under "Set up one-click Google sign-in" on the login page.

Data lives in the browser's localStorage. Use **Download backup** to move it to another device.
