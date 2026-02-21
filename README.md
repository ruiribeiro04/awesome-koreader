# Awesome KOReader [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome [KOReader](https://github.com/koreader/koreader) plugins, tools, patches, sync servers, and resources for e-ink reader enthusiasts.

KOReader is a free and open-source document viewer primarily aimed at e-ink readers. It supports PDF, DjVu, EPUB, FB2, and many more formats, running on Cervantes, Kindle, Kobo, PocketBook, reMarkable, and Android devices.

## Contents

- [Official Resources](#official-resources)
- [Plugins — AI & Assistants](#plugins--ai--assistants)
- [Plugins — Book Discovery & Downloads](#plugins--book-discovery--downloads)
- [Plugins — Reading Services Integration](#plugins--reading-services-integration)
- [Plugins — Sync & File Management](#plugins--sync--file-management)
- [Plugins — Highlights & Annotations](#plugins--highlights--annotations)
- [Plugins — Dictionary & Language](#plugins--dictionary--language)
- [Plugins — UI & Customization](#plugins--ui--customization)
- [Plugins — Comics & Manga](#plugins--comics--manga)
- [Plugins — RSS & Read-It-Later](#plugins--rss--read-it-later)
- [Plugins — Reading Tracking & Goals](#plugins--reading-tracking--goals)
- [Plugins — Utilities & Tools](#plugins--utilities--tools)
- [Plugins — Games & Entertainment](#plugins--games--entertainment)
- [Plugins — PocketBook Specific](#plugins--pocketbook-specific)
- [Sync Servers (Self-Hosted)](#sync-servers-self-hosted)
- [Desktop & External Tools](#desktop--external-tools)
- [Calibre Integration](#calibre-integration)
- [Patches & Customization](#patches--customization)
- [Themes & Icon Packs](#themes--icon-packs)
- [Guides & Tutorials](#guides--tutorials)
- [Community](#community)
- [Contributing](#contributing)

---

## Official Resources

- [KOReader](https://github.com/koreader/koreader) — The main KOReader application repository (25k+ ⭐).
- [KOReader User Guide](https://koreader.rocks/user_guide/) — Official user documentation.
- [KOReader Wiki](https://github.com/koreader/koreader/wiki) — Community-maintained wiki with setup guides and FAQ.
- [KOReader Website](https://koreader.rocks/) — Official project landing page.
- [koreader-base](https://github.com/koreader/koreader-base) — Base framework offering a Lua scriptable environment for creating document readers.
- [koreader-translations](https://github.com/koreader/koreader-translations) — Localization and translation files.
- [koreader/contrib](https://github.com/koreader/contrib) — Official collection of non-official plugins designed for KOReader (233+ ⭐).
- [koreader/doc](https://github.com/koreader/doc) — Hosted developer documentation.
- [crengine](https://github.com/koreader/crengine) — KOReader's CREngine fork for EPUB/FB2 rendering.
- [android-luajit-launcher](https://github.com/koreader/android-luajit-launcher) — Android NativeActivity-based launcher for LuaJIT.
- [KoboUSBMS](https://github.com/koreader/KoboUSBMS) — Helper to handle USBMS on Kobo in KOReader.

## Plugins — AI & Assistants

- [assistant.koplugin](https://github.com/omer-faruq/assistant.koplugin) — AI assistant supporting Claude, GPT-4, Gemini, DeepSeek, Ollama, and OpenRouter. Features stream mode, translation, Term X-Ray, Recap, and custom prompts (271+ ⭐).
- [koassistant.koplugin](https://github.com/zeeyado/koassistant.koplugin) — Another fork of the AskGPT assistant plugin with additional updates.

## Plugins — Book Discovery & Downloads

- [zlibrary.koplugin (ZlibraryKO)](https://github.com/ZlibraryKO/zlibrary.koplugin) — Z-Library client for KOReader: search and download books directly on your device (157+ ⭐).
- [zlibrary.koplugin (OctoNezd)](https://github.com/OctoNezd/zlibrary.koplugin) — Alternative Z-Library client for KOReader (152+ ⭐).
- [libgen-opds](https://github.com/krruzic/libgen-opds) — Library Genesis and OPDS bridge: search and download books via KOReader's OPDS search. Includes GoodReads most-read lists (41+ ⭐).
- [zotero.koplugin](https://github.com/stelzch/zotero.koplugin) — Browse and download documents from your Zotero collections on your e-reader (104+ ⭐).
- [audiobookshelf.koplugin](https://github.com/koreader/contrib) — Browse and download from your Audiobookshelf server (part of contrib).
- [legado.koplugin](https://github.com/pengcw/legado.koplugin) — Read web novels from Legado's open-source reading library on KOReader (110+ ⭐).
- [rakuyomi](https://github.com/hanatsumi/rakuyomi) — Manga reader plugin: browse and download manga from multiple sources directly in KOReader.

## Plugins — Reading Services Integration

- [hardcoverapp.koplugin](https://github.com/Billiam/hardcoverapp.koplugin) — Update your reading status on [Hardcover.app](https://hardcover.app) directly from KOReader.
- [beeminder.koplugin](https://github.com/cbrxyz/beeminder.koplugin) — Automatically log reading progress to Beeminder goals.
- [wallabag.koplugin](https://github.com/koreader/koreader) — Built-in Wallabag v2 integration for read-it-later articles.
- [gota.koplugin](https://github.com/koreader/contrib) — Access Raindrop.io bookmarks from KOReader.
- [karakeep.koplugin](https://github.com/koreader/contrib) — Access Karakeep bookmarks from KOReader.

## Plugins — Sync & File Management

- [TelegramDownloader.koplugin](https://github.com/Evgeniy-94/TelegramDownloader.koplugin) — Send files to your e-reader via a Telegram bot.
- [filebrowserplus.koplugin](https://github.com/koreader/contrib) — Run a Filebrowser server for wireless file management on your device.
- [AnnotationSync.koplugin](https://github.com/dani84bs/AnnotationSync.koplugin) — Lightweight plugin to keep annotations in sync between devices via cloud (23+ ⭐).
- [syncthing.koplugin](https://github.com/arthurrump/syncthing.koplugin) — Run Syncthing directly from within KOReader for seamless file sync (29+ ⭐).
- [supersync.koplugin](https://github.com/koreader/contrib) — Full metadata sync to cloud storage (Dropbox, WebDAV, etc.).
- [email-to-koreader.koplugin](https://github.com/koreader/contrib) — Receive documents and articles directly to your device via email.
- [Highlight-Sync](https://github.com/gitalexcampos/koreader-Highlight-Sync) — Sync highlights, notes, and bookmarks across multiple devices using WebDAV or Dropbox (88+ ⭐).

## Plugins — Highlights & Annotations

- [provider-webdav-highlights.koplugin](https://github.com/fairlygood/provider-webdav-highlights.koplugin) — Export KOReader highlights to a WebDAV target (21+ ⭐).
- [telegram-highlights.koplugin](https://github.com/koreader/contrib) — Send highlights to a Telegram bot with images.
- [remotenote.koplugin](https://github.com/koreader/contrib) — Type notes on another device for highlighted passages.

## Plugins — Dictionary & Language

- [anki.koplugin](https://github.com/Ajatt-Tools/anki.koplugin) — Generate Anki flashcards from dictionary lookups in KOReader (143+ ⭐).
- [dictionarymode.koplugin](https://github.com/koreader/contrib) — One-tap dictionary lookups while reading.
- [wordreference.koplugin](https://github.com/koreader/contrib) — Look up words on WordReference.
- [vocabularybuilder.koplugin](https://github.com/koreader/contrib) — Build vocabulary from lookups during reading.
- [memobook.koplugin](https://github.com/koreader/contrib) — Personal dictionary for terms and in-book memos.
- [zim-converter](https://github.com/Bartvelp/zim-converter) — Convert ZIM files (Kiwix/Wikipedia) to SQLite databases for the WikiReader plugin (25+ ⭐).

## Plugins — UI & Customization

- [ProjectTitle](https://github.com/joshuacant/ProjectTitle) — Enhanced cover browser UI plugin: custom title bar, fresh book listings, informative footer, matching book status page, and endless customization.
- [reader-menu-redesign.koplugin](https://github.com/koreader/contrib) — Redesigned reader menus and popups for a modern look.
- [Menu-Customizer](https://github.com/JoeBumm/Koreader-Menu-customizer) — Hide specific menus and plugin entries for a cleaner, focused interface (28+ ⭐).
- [iconschanger.koplugin](https://github.com/koreader/contrib) — Download and change icon packs.
- [illustrations.koplugin](https://github.com/koreader/contrib) — View and manage book illustrations in a dedicated gallery.

## Plugins — Comics & Manga

- [rakuyomi](https://github.com/hanatsumi/rakuyomi) — Full-featured manga reader plugin: browse, search, and download manga from multiple online sources.
- [comicreader.koplugin](https://github.com/KORComic/comicreader.koplugin) — Enhance comic and paged document reading with dual-page view (22+ ⭐).
- [comicmeta.koplugin](https://github.com/KORComic/comicmeta.koplugin) — Extract metadata from CBZ/CBR files as custom metadata (21+ ⭐).

## Plugins — RSS & Read-It-Later

- [miniflux.koplugin](https://github.com/AlgusDark/miniflux.koplugin) — Access a Miniflux instance to read RSS feed entries with offline capabilities (42+ ⭐).
- [readeck.koplugin (flip-rossi)](https://github.com/flip-rossi/readeck.koplugin) — Integration with your Readeck read-it-later instance (37+ ⭐).
- [readeck.koplugin (iceyear)](https://github.com/iceyear/readeck.koplugin) — Alternative Readeck plugin for KOReader (35+ ⭐).
- [opdsplus.koplugin](https://github.com/koreader/contrib) — Enhanced OPDS browser with advanced catalog features.
- [rssreader.koplugin](https://github.com/koreader/contrib) — Follow RSS feeds from a single screen.

## Plugins — Reading Tracking & Goals

- [readingstreak.koplugin](https://github.com/koreader/contrib) — Build reading habits and track consecutive reading days.
- [readinggoals.koplugin](https://github.com/koreader/contrib) — Set and monitor reading targets and progress milestones.
- [tbrplanner.koplugin](https://github.com/koreader/contrib) — Organize and schedule your To Be Read list.

## Plugins — Utilities & Tools

- [timeblock.koplugin](https://github.com/koreader/contrib) — Schedule KOReader reading windows with PIN-locked parental controls.
- [notes.koplugin](https://github.com/koreader/contrib) — Handwritten notes with stylus support.
- [crossword.koplugin](https://github.com/koreader/contrib) — Solve crosswords on your device.
- [calculator.koplugin](https://github.com/koreader/contrib) — Full-featured calculator with unit conversion.
- [digitalclock.koplugin](https://github.com/koreader/contrib) — Display time, date, and image as a clock.
- [readingruler.koplugin](https://github.com/Syakhisk/readingruler.koplugin) — Movable underline to guide reading on e-ink screens (27+ ⭐).
- [weather.koplugin](https://github.com/koreader/contrib) — Weather forecasts and conditions.
- [webbrowser.koplugin](https://github.com/koreader/contrib) — Text-based web browsing on your e-reader.
- [gotobed.koplugin](https://github.com/koreader/contrib) — Enforces bedtime by locking the device.
- [screenlockpin.koplugin](https://github.com/koreader/contrib) — Protect your KOReader with a PIN.
- [smartdelete.koplugin](https://github.com/koreader/contrib) — Enhanced file deletion with safety warnings.
- [weighttracker.koplugin](https://github.com/koreader/contrib) — Track weight measurements on your reader.
- [crashlogviewer.koplugin](https://github.com/koreader/contrib) — View and filter crash logs for troubleshooting.
- [airplanemode.koplugin](https://github.com/koreader/contrib) — Quick airplane mode toggle with plugin management.
- [todo.koplugin](https://github.com/koreader/contrib) — Simple to-do list app.
- [updatesmanager.koplugin](https://github.com/koreader/contrib) — Manage and control plugin and app updates.
- [appstore.koplugin](https://github.com/koreader/contrib) — Browse and install KOReader plugins and apps.
- [pixelart.koplugin](https://github.com/MoreFoxBeans/pixelart.koplugin) — Create pixel art on your e-ink device (32+ ⭐).
- [weatherlockscreen.koplugin](https://github.com/koreader/contrib) — Display weather information on your device's sleep screen.
- [mtastop.koplugin](https://github.com/koreader/contrib) — Real-time MTA bus arrivals and local weather.

## Plugins — Games & Entertainment

- [connections.koplugin](https://github.com/koreader/contrib) — NYT Connections puzzle game.
- [sudoku.koplugin](https://github.com/koreader/contrib) — Play Sudoku on your e-reader.
- [wordsearch.koplugin](https://github.com/koreader/contrib) — Solve word search puzzles on your device.

## Plugins — PocketBook Specific

- [pocketbookcover.koplugin](https://github.com/koreader/contrib) — Sync book cover to power-off screen on PocketBook devices.
- [pocketbooksync.koplugin](https://github.com/koreader/contrib) — Sync reading progress to PocketBook Library.

## Plugins — Archive of Our Own (AO3)

- [ao3downloader.koplugin](https://github.com/koreader/contrib) — Download and browse AO3 works directly from your e-reader.
- [ao3updater.koplugin](https://github.com/koreader/contrib) — Auto-update AO3 EPUBs with the latest chapters.

## Sync Servers (Self-Hosted)

- [koreader-sync-server](https://github.com/koreader/koreader-sync-server) — Official self-hostable KOReader sync server, built on OpenResty (Lua). Docker support included.
- [KoInsight](https://github.com/GeorgeSG/KoInsight) — Web-based reading stats dashboard that also acts as a kosync server. Docker deployable (266+ ⭐).
- [kosynco](https://github.com/orosoiu/kosynco) — Lightweight self-hosted sync server with Docker support and registration controls.
- [kosync-dotnet](https://github.com/jberlyn/kosync-dotnet) — Self-hostable sync server built with .NET and LiteDB. Admin panel included.
- [koreader-sync (b1n4ryj4n)](https://github.com/b1n4ryj4n/koreader-sync) — Python/FastAPI-based sync server with Docker support for ARM and AMD64.
- [Calibre-Web Automated](https://github.com/crocodilestick/calibre-web-automated) — Calibre-Web fork with built-in KOReader sync, OPDS server, and automated book processing.

## Desktop & External Tools

- [KoHighlights](https://github.com/noembryo/KoHighlights) — Desktop utility for viewing, editing, syncing, and exporting KOReader highlights to TXT, HTML, CSV, or Markdown.
- [KoInsight](https://github.com/GeorgeSG/KoInsight) — Self-hosted web dashboard for visualizing KOReader reading stats with charts and insights.
- [KOReader Highlight Importer (Obsidian)](https://obsidian.md/plugins?id=koreader-highlights-importer) — Obsidian plugin to import KOReader highlights and annotations directly into your vault.

## Calibre Integration

- [KOReader Sync (calibre plugin)](https://github.com/harmtemolder/koreader-calibre-plugin) — Synchronize metadata (progress, ratings, reviews, annotations) from KOReader sidecar files to calibre.
- [OPDS via Calibre Content Server](https://koreader.rocks/user_guide/) — Use Calibre's built-in content server with KOReader's OPDS browser to wirelessly browse and download your library.

## Patches & Customization

User patches are `.lua` files placed in `koreader/patches/` that modify KOReader's behavior without touching the source code.

- [KOReader.patches (SeriousHornet)](https://github.com/SeriousHornet/KOReader.patches) — Visual Overhaul Suite: rounded covers, custom widgets, status icons for Cover Browser and Project: Title.
- [KOReader.patches (joshuacant)](https://github.com/joshuacant/KOReader.patches) — Patches by the Project: Title creator.
- [KOReader.patches (loeffner)](https://github.com/loeffner/KOReader.patches) — Community patch collection with UI tweaks.
- [Koreader-Patches (angelsangita)](https://github.com/angelsangita/Koreader-Patches) — Community patches for interface customization.
- [koreader-patches (whatsnewsisyphus)](https://github.com/whatsnewsisyphus/koreader-patches) — Patch collection with themed customizations.
- [KOReader Patches Directory (kindlemodshelf)](https://kindlemodshelf.me/patches) — Curated directory of patches organized by category: essential, interface, status bar, screensaver, and standalone.

### Patch Categories

| Category | Description |
|----------|-------------|
| **Essential** | Core reading experience improvements |
| **Interface** | Menu and UI customization |
| **Status Bar** | Colors, progress bars, and visual tweaks |
| **Screensaver** | Sleep screen messages and behavior |
| **Standalone** | Extended functionality patches |

## Themes & Icon Packs

- [iconschanger.koplugin](https://github.com/koreader/contrib) — Plugin to download and switch between icon packs.
- [Visual Overhaul Suite](https://github.com/SeriousHornet/KOReader.patches) — Complete visual overhaul with custom SVG icons for book status (reading, abandoned, finished).
- [Project: Title Themes](https://github.com/joshuacant/ProjectTitle/wiki/User-Patches-for-Project-Title) — Extensive list of user patches specifically for theming Project: Title.

## Guides & Tutorials

- [KOReader User Guide (PDF)](https://koreader.rocks/koreader-user-guide.pdf) — Comprehensive official guide.
- [KOReader Wiki — User Patches](https://github.com/koreader/koreader/wiki) — Learn how to create and use user patches.
- [Developing Your First KOReader Plugin](https://kindlemodshelf.me/plugins) — Step-by-step guide covering environment setup, `_meta.lua`, `main.lua`, and a Hello World example.
- [OPDS Setup Guide](https://wotaku.wiki/guides/manga/opds) — Guide on setting up OPDS with Calibre, Kavita, Komga, and KOReader.
- [Self-Hosted eBook Library Guide](https://blog.rabu.me/self-hosted-library-koreader-calibre-sync-highlights-export-readwise/) — Complete walkthrough for self-hosting with KOReader, Calibre-Web, sync, and highlight export.
- [Project: Title Installation](https://github.com/joshuacant/ProjectTitle/wiki/Installation) — Detailed installation instructions for the Project: Title plugin.
- [Export Highlights to Obsidian](https://www.reddit.com/r/koreader/comments/1knkg1k/export_your_koreader_highlights_to_obsidian/) — Community guide for exporting KOReader highlights to Obsidian via JSON.

## Community

- [r/koreader](https://www.reddit.com/r/koreader/) — Reddit community for KOReader users.
- [MobileRead KOReader Forum](https://www.mobileread.com/forums/forumdisplay.php?f=276) — Long-standing forum for KOReader discussion.
- [GitHub Discussions](https://github.com/koreader/koreader/discussions) — Official GitHub Discussions.
- [KindleModShelf](https://kindlemodshelf.me/) — Community-maintained directory of KOReader plugins and patches.
- [koreader-plugin Topic on GitHub](https://github.com/topics/koreader-plugin) — Discover all repositories tagged with the `koreader-plugin` topic (41+ repos).

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](https://github.com/sindresorhus/awesome/blob/main/contributing.md) first.

If you know of a KOReader plugin, tool, or resource that isn't listed here, please open a pull request or issue.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Rui Ribeiro](https://github.com/ruiribeiro04) has waived all copyright and related or neighboring rights to this work.
