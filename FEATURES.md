# Built-in features for classroom-companion-os

Purpose: schoolwork and study

1. **prepare study and research files** — run classroom-companion-os-workspace. It creates ~/Documents/classroom-companion-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run classroom-companion-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/classroom-companion-os-session-plans/.
3. **check study and source readiness** — run classroom-companion-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/classroom-companion-os-workspace features/classroom-companion-os-plan features/classroom-companion-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for schoolwork and study:

1. **Zotero** — org.zotero.Zotero
2. **Foliate** — com.github.johnfactotum.Foliate
3. **VSCodium** — com.vscodium.codium

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for schoolwork and study:

1. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
2. **Thonny** — write and debug Python code (org.thonny.Thonny)
3. **Godot Engine** — build and test 2D and 3D games (org.godotengine.Godot)
4. **QGIS** — analyze geographic data and make maps (org.qgis.qgis)
5. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
6. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
7. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
8. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
9. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)
10. **GNOME Weather** — check local weather conditions (org.gnome.Weather)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
