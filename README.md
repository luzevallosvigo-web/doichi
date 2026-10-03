# Doichi (Gemini version)

Your German companion: Lesefreund, Satzdoktor, Sag's auf Deutsch!, Kaffeeklatsch.
It runs on Google's free Gemini API tier. Your API key is stored only on your device.

## 1. Get a free Gemini API key
1. Open https://aistudio.google.com/apikey and sign in with your Google account.
2. Click "Create API key" and copy it (it starts with "AIza…").

## 2. Put Doichi online (free, with GitHub Pages)
1. Create a free account at https://github.com.
2. Click "New repository", name it `doichi`, set it to Public, and create it.
3. Click "uploading an existing file" and drag in ALL files from this folder
   (index.html, sw.js, manifest.webmanifest, the 3 icon PNGs). Click "Commit changes".
4. Go to Settings → Pages → Source: "Deploy from a branch", Branch: `main`, folder `/ (root)` → Save.
5. After about a minute your app is at: https://YOUR-USERNAME.github.io/doichi/

The key is NOT in these files, so the repository can safely be public.

## 3. Install it on your phone
1. Open the link in Chrome (Android) or Safari (iPhone).
2. Chrome: menu ⋮ → "Install app" / "Add to Home screen". Safari: Share → "Add to Home Screen".
3. Open Doichi → scroll to "Einstellungen" → paste your key → "Verbindung testen".

## Models
- Modell (Lesefreund, Satzdoktor, Sag's): default `gemini-flash-latest` (always the current Flash).
- Schnelles Modell (Kaffeeklatsch): default `gemini-3.5-flash-lite`.
If a model stops working, tap "Verbindung testen" and pick another one from the list.

## Updating
Upload the changed file(s) to the same repository again. The app picks up the new version on next open.
