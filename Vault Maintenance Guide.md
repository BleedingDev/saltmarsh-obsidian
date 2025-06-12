# The Obsidian Vault Operator's Guide

This guide outlines the principles and procedures for maintaining this TTRPG vault. Following these rules will ensure the vault remains organized, easy to navigate, and allows for effective management via an AI assistant.

---

## Folder Structure and Purpose

This section details the purpose of each folder in the vault. Adhere to this structure strictly.

### Top-Level Folders

| Folder Name | Purpose |
| --- | --- |
| **`0. DM Screen`** | A Folder Note for a Kanban board of commonly used rules and notes. |
| **`0. Scratch Notes`** | A temporary dumping ground for quick notes that will be moved or deleted later. |
| **`1. The Party`** | Contains one note per player character, holding basic stats and info for quick reference. |
| **`1. World Almanac`** | The encyclopedia for your world. Contains all lore, locations, and modules. |
| **`2. Mechanics`** | The rulebook. Contains all game rules, monsters, items, spells, and NPCs. |
| **`2. Session Journals`** | The story of the campaign. One note per session, documenting events as they happen. |
| **`z_Assets`** | The dedicated folder for all attachments (images, PDFs, etc.). Set this as the attachment folder in Obsidian's settings. |
| **`z_Templates`** | The dedicated folder for all templates used with the Templater plugin. |

### `1. World Almanac` Sub-Folders

| Folder Name | Purpose | Notes |
| --- | --- | --- |
| **`Modules`** | Stores pre-written adventures. | Create one sub-folder per module, and within that, one note per chapter. |
| **`World`** | Your homebrew world's wiki. | Use nested notes and folders for continents, regions, cities, and specific locations like dungeons. |

### `2. Mechanics` Sub-Folders

This is the most granular section of the vault. The principle is **One Note per Thing**.

| Folder Name                 | Purpose                                                                                  | Usage Notes & AI Instructions                                                                   |
| --------------------------- | ---------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| **`Backgrounds`**           | One note per character background.                                                       | Low usage. Player-managed.                                                                      |
| **`Bestiary`**              | One note per monster, organized into sub-folders by sourcebook (e.g., `Monster Manual`). | **High Usage.** Crucial for linking in session notes. Create sub-folders for each book.         |
| **`Classes`**               | One note per player class.                                                               | Low usage. Players typically use physical sheets, books or D&D Beyond.                          |
| **`Dangers`**               | One note per trap or hazard.                                                             | Useful for linking specific traps mentioned in adventure notes.                                 |
| **`Deities`**               | One note per deity in your world.                                                        | Good for prep and linking when a god is mentioned.                                              |
| **`Dictionary`**            | One note per complex word.                                                               | A personal tool for vocabulary building.                                                        |
| **`Feats`**                 | One note per feat.                                                                       | Allows for linking feats from character sheets or NPC stat blocks.                              |
| **`Guilds and Groups`**     | One note per faction or organization.                                                    | Documents key members, goals, and lore for in-world groups.                                     |
| **`Items`**                 | One note per magic or significant item.                                                  | **High Usage.** Essential for tracking item properties and linking to loot in session journals. |
| **`Languages`**             | One note per language.                                                                   | Low usage. Can cause linking conflicts with similarly named things. Use with care.              |
| **`Non-Player Characters`** | One note per NPC.                                                                        | **High Usage.** Describes appearance, personality, and knowledge. Link to them constantly.      |
| **`Random Tables`**         | One note per random table.                                                               | Can be replaced by AI-powered templates for dynamic generation.                                 |
| **`Sound Board`**           | Notes containing lists of sounds for atmosphere.                                         | Low usage at the physical table.                                                                |
| **`Spells`**                | One note per spell.                                                                      | **High Usage.** Constantly linked and referenced during gameplay.                               |

---

## Prime Directives for the AI Vault Assistant

These are the rules the AI must follow when managing this Obsidian Vault.

#### DO:
- **Place Notes with Precision:** Every new note must be created in the specific folder that matches its content type as defined above.
- **Link, Don't Repeat:** Search before creating. If a note exists, link to it using `[[WikiLink Syntax]]`.
- **Create Atomic Notes:** One note per monster, spell, NPC, or location.
- **Use Session Journals for History:** Record all plot and party actions in `2. Session Journals`. World/Mechanics notes must remain static.
- **Confirm and Report:** After completing a task, confirm what you did and where.

#### DON'T:
- **Create Files in the Root Directory:** Everything has a home in a subfolder.
- **Create "List" Pages:** The folder structure and search function serve this purpose.
- **Guess File Paths:** Adhere strictly to the defined structure.
- **Overwrite Content Without Permission:** Always prefer to `append` or `patch` information. Ask before replacing content.
- **Delete Without Confirmation:** Always state the full file path and ask for explicit confirmation before deleting.