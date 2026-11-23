# mediaverse.studio

The website of MediaVerse Studio, served by GitHub Pages from this repository's `main` branch at
https://mediaverse.studio. Plain HTML and one stylesheet, no build step: edit a page, commit, push.

- `index.html`: what the program is, the platforms, the features, the beta call and the roadmap. Keep the platform pills and the roadmap columns honest: a feature is "Working" only when it has been used on a real device, "new" or "in testing" until the owner has tried it, and "Planned" when nothing is built.
- `privacy.html`: what the program sends where. Keep it in step with the program (every online service it
  contacts is listed); change the date at the top with every change.
- `support.html`: contact, thanks, trademarks.
- `CNAME`: the custom domain. DNS for mediaverse.studio is managed at Squarespace.
- `cast/receiver.html`: the page Google Cast devices load (App ID 0E81A85C).

## Before the application's repository goes public

- Add the link to https://github.com/MediaVerseStudio/MediaVerse-Studio on the home page (the "Free, and it stays free" section and the footer) and on the support page, and change "moving to a public GitHub repository" to plain words. Until it is public the link would not open.
- Check `privacy.html` against the build that is released (every service the program contacts, the Jellyfin and Android paragraphs) and change its date.
- Screenshots show an invented demo library (`img/`); new ones for the Jellyfin settings, the lyrics editor and the re-rip list are still to be made from the demo library.
