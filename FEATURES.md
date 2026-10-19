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
