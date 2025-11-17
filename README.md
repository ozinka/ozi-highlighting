# Ozi Work Tools

A lightweight Visual Studio Code extension providing quick date-time line insertion commands and minimal syntax highlighting for plain text files.

## Features

### 🕒 Date-Time Line Insertion
Quickly insert a formatted separator line with the current date and time:

- **Insert Below (Alt + Enter)** – Inserts the line *after* the current cursor.
- **Insert Above (Alt + Shift + Enter)** – Inserts the line *before* the current cursor and moves the caret upward.

The inserted line looks like this:

— ✄ ——— 2025.10.17 17:43 —————––

### 🎨 Syntax Highlighting (Optional)
- Basic syntax highlighting for `.txt` files labeled with the language id `ozi-work`.
- Word suggestions and IntelliSense are **disabled** for distraction-free editing.

### ⚙️ Usage
1. Open a `.txt` file.
2. Set the language mode to **Ozi Work** (bottom-right corner → “Select Language Mode” → choose *Ozi Work*).
3. Use one of the keybindings:
   - `Alt + Enter` → Insert date-time line **below**
   - `Alt + Shift + Enter` → Insert date-time line **above**

### 🔧 Extension Commands
| Command ID | Description | Default Shortcut |
|-------------|-------------|------------------|
| `oziWork.insertDateTimeLineAfter` | Insert a date-time separator line after the cursor | `Alt + Enter` |
| `oziWork.insertDateTimeLineBefore` | Insert a date-time separator line before the cursor | `Alt + Shift + Enter` |

### 🧩 Motivation
Originally created as a personal utility to help organize text notes, logs, and ideas without leaving the keyboard.

### 💡 Example Use Cases
- Inserting timestamp separators in logs or notes.
- Structuring brainstorming sessions.
- Keeping quick developer diaries.

---

**Enjoy your clean and practical note workflow with Ozi Work Tools!**
