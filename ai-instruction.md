# Repository Instruction Manual for AI Assistants

This file outlines the rules, styling constraints, and structural behaviors that any AI assistant (including LLMs and agentic coders) must follow when interacting with this repository.

---

## 🛑 Rule 1: Mandatory Placement & Confirmation
* **Ask Before Writing:** Before creating, moving, or writing any files, the AI **must** ask the developer for confirmation on:
  1. The exact folder path where the file should reside.
  2. The naming convention for the file and directory.
* **No Guessing:** If the directory path is uncertain, state this clearly, list the available folders, and wait for developer input.

## 📂 Rule 2: Hierarchical Directory Structure
All educational materials and certifications must be organized in a nested manner:
`[Academy or Organization Name] / [Course Folder Name] / [Files]`

* **Example:** `Open AI Academy/Open AI Foundation 1/`
* **Folder Contents:** Folder contents are creator freedom.

## ✍️ Rule 3: Visual Formatting & Spacing Guidelines
* **Readability Container:** Group navigation guides or list entries inside a blockquote (`>`) to create a "box-like" visual container.
* **Spacing:** Insert horizontal rules (`---`) and double line breaks between file entries to prevent visual clutter.
* **Relative Links Only:** Never use absolute paths (like `file:///C:/...` or `file:///D:/...`). Always use relative paths (`./file.md`) so links work globally on GitHub.
* **Grammar:** Use clear sentence structures with proper comma placements and spacing.
