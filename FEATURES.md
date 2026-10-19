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
