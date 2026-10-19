# Built-in features for postscript-studio-os

Purpose: blog publishing

1. **prepare a creative project** — run postscript-studio-os-workspace. It creates ~/Documents/postscript-studio-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run postscript-studio-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/postscript-studio-os-session-plans/.
3. **check project and export readiness** — run postscript-studio-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/postscript-studio-os-workspace features/postscript-studio-os-plan features/postscript-studio-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for blog publishing:

1. **Inkscape** — org.inkscape.Inkscape
2. **Krita** — org.kde.krita
3. **Kdenlive** — org.kde.kdenlive

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for blog publishing:

1. **Blender** — create 3D assets and animations (org.blender.Blender)
2. **OBS Studio** — record or stream sessions (com.obsproject.Studio)
3. **Audacity** — edit audio recordings (org.audacityteam.Audacity)
4. **Ardour** — record and mix multitrack audio (org.ardour.Ardour)
5. **darktable** — develop RAW photos (org.darktable.Darktable)
6. **Scribus** — lay out print-ready publications (org.scribus.Scribus)
7. **VLC** — review media files (org.videolan.VLC)
8. **Mixxx** — prepare and mix DJ sets (org.mixxx.Mixxx)
9. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
10. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
2. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
3. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
4. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
5. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
6. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
7. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
8. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
9. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
10. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
11. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
12. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
13. **Zotero** (org.zotero.Zotero) — manage research sources and citations.
14. **Calibre** (com.calibre_ebook.calibre) — organize ebooks and convert documents.
15. **Foliate** (com.github.johnfactotum.Foliate) — read EPUB books.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.
