# Personal Life OS

A mobile-first, glassmorphism personal dashboard built with plain HTML, CSS and JavaScript.

## Features
- Responsive dashboard for phone, tablet and desktop
- Task creation, editing, completion, deletion, categories, priorities and due dates
- Monthly calendar with date-based task view
- Project tracker with progress
- Notes and quick capture
- Manual income and expense tracking (INR)
- Habit checklist
- Optional 4–8 digit PIN lock
- JSON backup export/import
- Browser notification permission prompt
- Local storage: no account or backend required

## Run locally
Open `index.html` in a modern browser. For best PWA/install support, use a local web server:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Deploy with GitHub Pages
1. Create a new GitHub repository, for example `personal-life-os`.
2. Upload the contents of this folder to the repository root (not the containing folder).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. Wait for the Pages URL to appear. Open it on Android Chrome and choose **Add to Home screen**.

## Privacy and security notes
- Tasks, notes, projects and finance entries are stored in the browser's local storage on this device.
- The optional PIN is a convenience lock, not strong encryption. It does not protect data from someone with access to browser developer tools or the device profile.
- Do not store passwords, bank credentials, identity numbers or highly sensitive information here.
- Browser notifications are permission-based and may not fire if the browser is closed or the device restricts background activity.
- Google Fonts requires an internet connection; the app itself has no runtime framework dependency.

## Project structure
```
personal-life-os/
├── index.html
├── styles.css
├── app.js
├── manifest.json
├── README.md
└── assets/
    └── icon.svg
```
