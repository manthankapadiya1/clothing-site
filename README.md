# Wear the Story

A responsive clothing-style journal built with plain HTML, CSS, and vanilla JavaScript. It is designed as a polished front-end project for a classroom presentation and can be published as a static GitHub Pages site.

## Run it locally

1. Download or clone this folder.
2. Open `index.html` in a modern browser. No package installation, build step, or server is required.
3. For a local web-server preview, open the folder in VS Code and use the Live Server extension, or run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

The page uses remotely hosted Unsplash photos and Google Fonts, so those visual assets need an internet connection. The site itself has no backend or external JavaScript dependencies.

## Demo walkthrough

1. Start at the editorial landing page and choose **Explore the journal**.
2. Select a category or search for a style, place, or fabric. Expand **Make it yours** on a card to show customization ideas and a short fabric note.
3. Tap the heart on a style. The saved count and **Saved for later** collection update immediately and persist in that browser using localStorage. Remove an item from either its card or the saved collection.
4. Use the moon/sun control to switch themes; the selection persists in that browser.
5. Open **Sign in** and try both tabs. Registration asks for a name, valid email, and a password of at least six characters. The form only demonstrates client-side validation; it does not authenticate anyone or store account credentials.
6. The newsletter form is also a front-end demo and does not submit or send an email.

Wishlist and theme data stay in the current browser. Clearing that browser's site data removes them. Do not enter real credentials.

## Publish with GitHub Pages

1. Create a new GitHub repository and add `index.html`, `style.css`, `script.js`, and this README at the repository root.
2. Commit and push the files to the repository's default branch.
3. On GitHub, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select the default branch and the `/ (root)` folder, then save.
4. Wait for the Pages deployment to finish. GitHub will show the published site URL in the Pages settings.

For a project repository, keep the three site files at the repository root so `index.html` is served as the homepage.

## Project files

- `index.html` — semantic page structure, style journal, account dialog, and footer.
- `style.css` — responsive editorial design, light/dark themes, and reduced-motion support.
- `script.js` — style data, filtering, search, wishlist persistence, theme control, and demo form validation.

## Presentation note

This is a static front-end demonstration. Account forms provide validation and a temporary success message only; there is no database, server, or real sign-in. Style text and customization ideas are introductory summaries, not a guide to wearing culturally significant clothing on every occasion.
