# Built-in features for buildscape-os

Purpose: architecture concepts

1. **prepare a technical project** — run buildscape-os-workspace. It creates ~/Documents/buildscape-os-workspace/ with Design, Builds, Logs folders.
2. **plan a build or maintenance session** — run buildscape-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/buildscape-os-session-plans/.
3. **check technical change readiness** — run buildscape-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/buildscape-os-workspace features/buildscape-os-plan features/buildscape-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for architecture concepts:

1. **GIMP** — org.gimp.GIMP
2. **Inkscape** — org.inkscape.Inkscape
3. **Krita** — org.kde.krita

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for architecture concepts:

1. **OpenSCAD** — model parametric 3D parts in code (org.openscad.OpenSCAD)
2. **KiCad** — design circuits and PCBs (org.kicad.KiCad)
3. **Arduino IDE** — write and upload microcontroller sketches (cc.arduino.IDE2)
4. **PrusaSlicer** — prepare models for 3D printing (com.prusa3d.PrusaSlicer)
5. **DB Browser for SQLite** — inspect SQLite databases (org.sqlitebrowser.sqlitebrowser)
6. **Wireshark** — inspect network traffic (org.wireshark.Wireshark)
7. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
8. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
9. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
10. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **QElectroTech** (org.qelectrotech.QElectroTech) — draw electrical schematics and wiring diagrams.
2. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
3. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
4. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
5. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
6. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
7. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
8. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
9. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
10. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
11. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
12. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
13. **Disk Usage Analyzer** (org.gnome.baobab) — find large files and manage storage.
14. **Flatseal** (com.github.tchx84.Flatseal) — review Flatpak app permissions.
15. **VSCodium** (com.vscodium.codium) — edit code and project files.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **KDevelop** (org.kde.kdevelop) — edit, navigate, build, and debug software projects.
2. **Kate** (org.kde.kate) — edit configuration, code, notes, and structured project files.
3. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
4. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.
5. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
6. **Ark** (org.kde.ark) — open and create common project archive files.
7. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
8. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.
9. **KDiff3** (org.kde.kdiff3) — compare and merge source files and directory trees.
10. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
11. **Marble** (org.kde.marble) — explore maps and a virtual globe for geographic context.
12. **KStars** (org.kde.kstars) — plan sky observations and explore astronomy simulations.
13. **KGeography** (org.kde.kgeography) — practice country, capital, and map recognition.
14. **Rnote** (com.github.flxzt.rnote) — sketch diagrams, write by hand, and annotate pictures or documents.
15. **Konsole** (org.kde.konsole) — run shell commands and inspect development or system tasks.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.

## Blender included in every setup

Blender (org.blender.Blender) is included in every setup for 3D modeling, animation, rendering, and video editing. Installers fetch it from Flathub; Blender’s own license and terms apply.

## Fifteen additional purpose-specific applications

The setup adds these Flathub applications for architecture concepts. Applications are fetched from Flathub by the setup script; each app keeps its own licensing and terms.

1. **PDF Arranger** (com.github.jeromerobert.pdfarranger) — Reorder, rotate, split, and merge PDF pages.
2. **LocalSend** (org.localsend.localsend_app) — Transfer files directly between nearby devices on your local network.
3. **Joplin** (net.cozic.joplin_desktop) — Organize notes and checklists in notebooks.
4. **KBackup** (org.kde.kbackup) — Create user-selected backup archives of files and folders.
5. **Déjà Dup** (org.gnome.DejaDup) — Create user-configured file backups to a chosen destination.
6. **KRename** (org.kde.krename) — Batch rename photo, document, and project files.
7. **Tellico** (org.kde.tellico) — Catalog books, media, games, and other collections.
8. **Skanpage** (org.kde.skanpage) — Scan and arrange multipage documents from a connected scanner.
9. **Merkuro** (org.kde.merkuro) — Organize calendars, contacts, and tasks.
10. **Kontact** (org.kde.kontact) — Organize personal email, contacts, calendars, and tasks.
11. **KMyMoney** (org.kde.kmymoney) — Track personal accounts, budgets, and expenses locally.
12. **KAlarm** (org.kde.kalarm) — Schedule reminders and personal alarms.
13. **KClock** (org.kde.kclock) — Use alarms, timers, and a stopwatch.
14. **Marknote** (org.kde.marknote) — Organize lightweight Markdown notes.
15. **KleverNotes** (org.kde.klevernotes) — Create and organize Markdown notes.
