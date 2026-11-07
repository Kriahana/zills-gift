# A Little Birthday Adventure

A small, static birthday puzzle gift. Open `index.html` locally, or publish this folder with GitHub Pages — no server or login is needed.

## What's inside

A five-step flow: a short (very serious) personality quiz → a wish → a jigsaw puzzle → the reveal. The puzzle is a 4×4 drag-and-drop jigsaw built from the bundled `birthday-art.jpg`, with a **Hint** button and a **Reset** button. It works with mouse and touch.

## Files

- `index.html` — everything (styles, quiz, wish, puzzle, letter). Self-contained.
- `birthday-art.jpg` — the original illustration. Keep this filename; the puzzle crops it into pieces.

## Try it locally

Just double-click `index.html`. To test the phone layout, shrink the browser window or use the browser's device toolbar.

## Publish with GitHub Pages

1. Create a new public GitHub repository (for example `birthday-surprise`).
2. Add `index.html`, `birthday-art.jpg`, and this README at the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to finish publishing. Its URL appears in the Pages settings. Open that URL on a phone to check it before sharing.

## Privacy / wishes

No backend is configured and nothing is sent to a server.

- **"Keep it just for me"** sends and stores nothing.
- **"Share my wish with you two"** saves the wish (with a timestamp) in that browser's local storage only, so the birthday girl can show it to her friends in person. It is not sent anywhere, and the device/browser may clear it.

## Customize

- **Age / final message** — edit the `#final` section (heading, polaroid caption, and the letter) in `index.html`.
- **Quiz questions** — edit the `QUESTIONS` array near the top of the `<script>`.
- **Puzzle size** — change `COLS`/`ROWS` (both set to `4`); the layout adapts automatically.
