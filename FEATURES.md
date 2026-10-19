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
