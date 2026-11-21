# Bible Notes

## Download and set up (easiest)

1. Download [`Bible Notes.zip`](Bible%20Notes.zip) from this repo (open it on GitHub and click **Download raw file**).
2. Unzip it anywhere.
3. Install [Obsidian](https://obsidian.md), choose **Open folder as vault**, and select the unzipped `Bible Notes` folder.
4. Start at `Notes/Table of Contents.md`.

Not using Obsidian? The vault is plain Markdown, so any Markdown editor or viewer can open the unzipped folder (links are Obsidian-style `[[wikilinks]]`, which some viewers show as plain text).

The zip leaves out the KJV page scans (`.jp2` images) to keep it small; the Markdown text is all included.

An [Obsidian](https://obsidian.md) vault for Bible study notes, with the scripture text stored alongside so chapters can be linked and read in place.

## Structure

- `Notes/` — the study notes, starting at `Notes/Table of Contents.md`
  - `Tanakh/` — Torah, Prophets, Writings (traditional Hebrew ordering, with Christian OT order also supported)
  - `Brit-Chadashah/` — the New Testament (Gospels, Acts, Epistles, Revelation)
  - `Apocrypha/` — deuterocanonical books
  - Each book note has chapter navigation and previous/next book links.
- `Scripture - ...` — Bible texts used by the notes:
  - English WEBU read-aloud version (`.txt`, per chapter)
  - Berean Standard Bible (BSB)
  - King James Version (KJV)
  - World Messianic Bible (WMB)
  - Markdown copies of chapters for the versions above, so they link cleanly from notes.
- `sortspec.md` — folder/file ordering spec for the notes.

## Usage

Open the repository folder as a vault in Obsidian and start from `Notes/Table of Contents.md`.

## Licensing

- KJV, WMB and WEB(U) are public domain.
- BSB is released under Creative Commons; see https://berean.bible for current terms.

See `copr.htm` in the WEBU folder for details. Check each source before redistributing.
