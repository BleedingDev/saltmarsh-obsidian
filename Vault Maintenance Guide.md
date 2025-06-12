# The Obsidian Vault Operator's Guide

This guide outlines the principles and procedures for maintaining this TTRPG vault. Following these rules will ensure the vault remains organized, easy to navigate, and allows for effective management via an AI assistant.

---

### **Prime Directives for the AI Vault Assistant**

These are the rules the AI must follow when managing this Obsidian Vault.

#### **DO:**

*   **DO: Place Notes with Precision.**
    *   Every new note must be created in the specific folder that matches its content type. Ask for clarification if the correct folder is ambiguous.
    *   *Example:* A new spell note goes into `2. Mechanics/Spells/`.

*   **DO: Link, Don't Repeat.**
    *   The core principle is **One Idea, One Note**. Before creating a new note, search the vault to see if it already exists. If it exists, link to it using `[[WikiLink Syntax]]`.
    *   *Example:* When noting a meeting with an NPC, link to their existing note: `"...met with [[Gellan Primewater]]..."`.

*   **DO: Create Atomic Notes.**
    *   One note should contain one monster, one spell, one NPC, or one location. This is non-negotiable.
    *   *Example:* To add Goblins and Orcs, create two separate files: `Goblin.md` and `Orc.md` in the Bestiary.

*   **DO: Use Session Journals for History.**
    *   The `2. Session Journals` folder is the *only* place to record the plot and the party's actions. World and Mechanics notes should remain static descriptions.
    *   *Example:* If the party destroys a house, note this in the journal. Do not change the original note for the house. `"...the party destroyed the [[Haunted House on the Hill]]..."`.

*   **DO: Confirm and Report.**
    *   After completing a task, always confirm what you have done and where you have done it.
    *   *Example Response:* "I have created the note `2. Mechanics/Items/Helm of Brilliance.md` as you requested."

#### **DON'T:**

*   **DON'T: Create Files in the Root Directory.**
    *   NEVER create a new note in the top-level folder of the vault (this guide is the one exception). Every piece of information has a home in one of the numbered subfolders.

*   **DON'T: Create "List" Pages.**
    *   NEVER create a note titled "List of Spells" or "Monsters in the Dreadwood". The folder structure and search functionality serve this purpose.

*   **DON'T: Guess File Paths.**
    *   NEVER invent a new folder structure. Adhere strictly to the existing folders. If a user asks to save something that doesn't fit, ask them where it should go.

*   **DON'T: Overwrite Content Without Permission.**
    *   NEVER use the `update` or `create` functions on an existing file without explicit instruction. Prefer to `append` or `patch` information to avoid data loss. Always ask before replacing content.

*   **DON'T: Delete Without Confirmation.**
    *   NEVER delete a file unless the user explicitly confirms the action. Always state the full path of the file you intend to delete before asking for confirmation.