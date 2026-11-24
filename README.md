# Meshrelay Website

A responsive, static product landing page for Meshrelay, an experimental Android-first offline mesh messaging application.

## Local preview

Open `index.html` in a browser, or run a static server:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080.

## Deploy to Vercel

Import this repository into Vercel. No build command or framework preset is required; set the output directory to `.` (or leave the static-site default).

## Android download

The primary download CTA currently links to the Meshrelay GitHub Releases page:
https://github.com/DeadPoet404/NEXORA/releases

Once an APK is published, you can either keep the Releases page link or change the button in `index.html` to the direct asset URL.

## Product accuracy

This page describes capabilities reflected in the Meshrelay source repository. It explicitly identifies the project as experimental and does not claim end-to-end encryption or guaranteed emergency delivery.
