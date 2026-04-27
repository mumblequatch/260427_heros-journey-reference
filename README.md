# Hero's Journey Reference

Single-file HTML reference document on Joseph Campbell's monomyth, Christopher Vogler's screenwriting adaptation, and the structures that argue with both. Includes successful and unsuccessful film/TV/novel examples, alternative frameworks (Harmon, Murdock, Hudson, Snyder, Yorke, McKee, Truby, the Story Spine, kishōtenketsu), a verified Further Reading list, a deliberately-omitted list, and end notes for offline-only resources.

## Files

- `index.html` — the entire reference. Self-contained: HTML, CSS, JavaScript inline. No build, no dependencies. Works from `file://` and from any static host.
- A Bear-import-ready `heros-journey-reference.md` is generated separately (lives in `~/Downloads/` after build). Drop it in any folder and import via Bear → File → Import From → Markdown Folder.

## Deploy to GitHub Pages

1. Push this repo to GitHub.
2. Settings → Pages → Build and deployment → Source: **Deploy from a branch** → Branch: **main** / **(root)** → Save.
3. The page will live at `https://<user>.github.io/<repo>/`.

## Local use

Open `index.html` directly in any browser. The page works fully offline. The Markdown export uses `Blob` + `URL.createObjectURL` and works from `file://`.

## Editing

All content is inline in `index.html`. To update a section, edit the corresponding `<section>`. The Bear-import Markdown is a separate hand-maintained file.

## Link verification

Every external link in the page and in the Markdown export was live-fetched at build time and confirmed to return HTTP 200. Offline-only resources (out-of-print books, books still in print but with no free online edition) are catalogued in the End Notes section with full bibliographic detail and ISBNs.

If a link rots, the fix is either: (1) replace with the Wayback Machine snapshot and note the original URL, or (2) move the resource to End Notes and update the Further Reading entry to drop the link.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Reuse with attribution.
