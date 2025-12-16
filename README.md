# Wound Vac Tracker (PHI‑Free) — Web App

This is a single‑page web app you can host on GitHub Pages and use on your iPhone/iPad immediately.

## Features
- PHI‑free tracking: Device ID/Barcode, Status, Unit/Room/Bed
- Camera barcode scanning (html5-qrcode)
- Dashboard counts + searchable list
- Local storage (data stays on the device/browser)
- Export CSV + JSON backup; Import JSON backup

## IMPORTANT (Camera Scanning)
iPhone/iPad camera scanning requires the app be served from **HTTPS**.
GitHub Pages is HTTPS, so it works well.

## Deploy on GitHub Pages (no terminal)
1. Create a GitHub repo (e.g., `woundvac-tracker`)
2. Upload `index.html` to the repo root
3. Repo Settings → Pages → Build and deployment
   - Source: Deploy from a branch
   - Branch: `main` / root
4. Wait a minute. Your site URL will appear (https://<user>.github.io/<repo>/)

## Use on iPhone
1. Open the GitHub Pages URL in Safari
2. Share → Add to Home Screen

## PHI‑free policy
Do **not** enter patient name, MRN, DOB, or any identifiers. Use only Unit/Room/Bed and device details.

