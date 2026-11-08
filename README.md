# Japanese Phrases for Travelers

A single-page phrasebook of common Japanese phrases for tourists, with pronunciations written for American English speakers. Includes search, a "Hear it" button (uses your device's Japanese voice), and a "Show" button that displays a phrase in large text to show staff.

## Publish with GitHub Pages

1. Create a new public repository (for example `japanese-phrases`).
2. Upload `index.html` and this `README.md` to the repository root.
3. Go to **Settings → Pages**, set the source to **Deploy from a branch**, choose `main` and `/ (root)`, and save.
4. After a minute or so the site is live at `https://<your-username>.github.io/<repo-name>/`.

It's one static file with no build step or dependencies. Add it to your phone's home screen for quick access, and open it once on Wi-Fi before you travel, since the page itself doesn't cache for offline use.

## Editing phrases

Phrases live in the `SECTIONS` array near the bottom of `index.html`. Each one is:

```
["English", "日本語", "Romaji", "how-an-american-says-it", "optional note"]
```
