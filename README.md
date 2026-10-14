# Ad Board

A Miro-style canvas for organising ad creatives. Drop in images and videos, tag each one by **angle**, **desire** and **avatar**, then regroup the whole board by any of those tags.

## Use it

Open `index.html` in Chrome or Safari, either double-clicked from Finder or served through GitHub Pages.

- **Add media**: click **+ Add media** to pick files, drag them onto the canvas, or paste a screenshot. Accepts PNG, JPG, GIF, WebP, MP4 and WebM.
- **Freeform**: drag cards anywhere. Drag the background to pan. Pinch or ctrl+scroll to zoom. **Fit** brings every card into view.
- **Angle / Desire / Avatar**: each view groups the cards into columns by that tag. Drag a card into another column to retag it.
- **Tagging**: click a card to set its tags, add notes, or star it as a winner. New tags you type are remembered.
- **★ Winners**: show only starred cards.

## Where your data lives

Everything is saved in the browser you open the board in (IndexedDB). Nothing is uploaded to GitHub or anywhere else.

- Each browser keeps its own board, so use the same one every time.
- Clearing site data for the page erases the board.
- The repo holds only the app, never your creatives.

## Hosting on GitHub Pages

Settings → Pages → Deploy from branch → `main` / root. The board will be at `https://<user>.github.io/ad-board/`. A Pages site is a different address from the local file, so it starts with its own empty board.
