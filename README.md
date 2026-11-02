# HomeMate

**Need it? Add it. Someone gets it.**

GitHub-ready, zero-cost starter version of HomeMate.

## Publish with GitHub Pages

1. Create a new **public** GitHub repository, for example `homemate`.
2. Upload `index.html` and `manifest.json` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. GitHub will give you a public `github.io` URL.

This version works as a mobile-friendly web app and saves demo data in the browser.

## Important
This is the GitHub/PWA starter. The next version should connect the existing HomeMate Firebase-ready code to Firebase Authentication + Firestore so multiple family phones can see the same list in real time.

Do not publish Firebase API keys or production secrets in this README. Firebase web configuration is normally client-side, but Firestore Security Rules must properly restrict family data before real users are onboarded.
