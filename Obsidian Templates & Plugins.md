## 🧱 1. Introduction to Obsidian Templates

**Templates** in Obsidian help you quickly insert pre-written structures — such as meeting notes, daily logs, project outlines, or documentation sections — into any note.

### 🔧 Enabling the Templates Plugin

1. Open **Settings → Core Plugins**
2. Toggle **Templates** ON
3. Go to **Settings → Templates**

   * **Template folder location** → choose or create a folder like `Templates/`
   * **Date format** → e.g., `YYYY-MM-DD`
   * **Time format** → e.g., `HH:mm`

---

## 🧩 2. Creating and Using Templates

### 🪶 Example: Daily Note Template

Create a new file in your Templates folder:

```markdown
# 📅 Daily Note - {{date}}

## 🌤 Overview
- Focus: 
- Priority: 

## 🧠 Notes
- 

## ✅ Tasks
- [ ] 

## ⏰ Time Log
{{time}}
```

To use:

1. Open a new note
2. Press `Ctrl + P` → search **“Insert Template”**
3. Choose your daily note template

---

## ⚙️ 3. Community Plugins Overview

Community Plugins extend Obsidian far beyond note-taking — they can automate workflows, manage projects, visualize data, and much more.

### ⚠️ Enable Community Plugins

1. Go to **Settings → Community Plugins**
2. Turn off **Safe Mode**
3. Browse and install plugins from the **Community Plugin Browser**

---

## 🧰 4. Essential Plugins for Your [[sandbox vault]]

| Plugin              | Purpose                                           | Usage Idea                                                       |
| ------------------- | ------------------------------------------------- | ---------------------------------------------------------------- |
| **Templater**       | Dynamic templating (advanced)                     | Add JavaScript logic, date math, or note metadata into templates |
| **Dataview**        | Turns notes into databases                        | Query project statuses, logs, or contacts                        |
| **Periodic Notes**  | Auto-generate daily/weekly/monthly note templates | Ideal for time-based journaling                                  |
| **QuickAdd**        | Automate template insertion and capture flows     | Add “New Project” or “New Task” commands                         |
| **Calendar**        | Visual calendar interface for daily notes         | Click to open notes by date                                      |
| **Advanced Tables** | Easier Markdown table editing                     | Clean formatting and auto-alignment                              |

![[sandbox vault]]

---

## 🧠 5. Example Sandbox Workflow

You can use your **[[sandbox vault]]** to safely experiment:

### 🧩 Step 1: Create Folders

```
📂 sandbox vault
 ┣ 📂 Templates
 ┣ 📂 Projects
 ┣ 📂 Notes
 ┗ 📂 Archive
```

### 🧩 Step 2: Add a Template

Inside `Templates/`, add `Project Template.md`:

```markdown
# 🗂 Project: {{title}}

## 🧾 Description
{{cursor}}

## 📅 Timeline
- Start: {{date}}
- Due: 

## ✅ Tasks
- [ ] Task 1
- [ ] Task 2
```

### 🧩 Step 3: Test Template Insertion

* Create a note under `Projects/`
* Run **Insert Template → Project Template**
* Fill in placeholders
* Experiment with **Templater** syntax like `<% tp.date.now("YYYY-MM-DD") %>`

---

## 🚀 6. Tips for Power Users

* Combine **Dataview** with **Templates** to track tasks or databases.
* Store **reusable template blocks** like headers or signatures separately.
* Use **QuickAdd Macros** to streamline repetitive workflows (e.g., daily logging).
* Keep your **[[sandbox vault]]** isolated for plugin tests — once stable, export templates to your main vault.

---

