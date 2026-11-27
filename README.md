# mediaverse.studio

The website of MediaVerse Studio, served by GitHub Pages from this repository's `main` branch at
https://mediaverse.studio. Plain HTML and one stylesheet, no build step: edit a page, commit, push.

| Page | What it holds |
|---|---|
| `index.html` | The short overview: organize, fix, share, and a card for each platform |
| `windows.html` | The Windows program in depth, and the comparison with other players |
| `android.html`, `tv.html`, `jellyfin.html` | Each in depth |
| `linux.html` | The Linux plan. Nothing is listed as working until it has been tried on Linux |
| `roadmap.html` | Working, in beta testing, next, planned; the beta call |
| `download.html` | The current release, what changed, checksums, the code signing policy |
| `privacy.html` | What the program sends where |
| `support.html` | Help, the beta, thanks, credits, trademarks |
| `cast/receiver.html` | The page Google Cast devices load (App ID 0E81A85C) |
| `CNAME` | The custom domain. DNS for mediaverse.studio is managed at Squarespace |

The header navigation is repeated in every page: change it everywhere.

Keep the pages honest: a feature is "working" only when it has been used on a real device, "new" or "in testing"
until then, and "planned" when nothing is built.

## At each release

- `download.html`: links, sizes, SHA-256 values, date and what changed. Also the version on the other pages
  (search for the old number).
- `privacy.html`: every online service the program contacts, and the permissions the apps ask for; change the date.
- Screenshots (`img/`) show the invented demo library (`tools/make-demo-library.ps1` in the application repository).
  Use a copy in a neutral folder, a throwaway data folder, and replace computer names and network addresses before
  capturing. The 2026-11-27 set came from the desktop and TV pages run in Electron and the Android app on an emulator.
