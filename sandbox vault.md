Read more at [[User Experience/Obsidian Templates & Plugins]]
## 🧰 What Is a Sandbox Vault?

Think of a **sandbox vault** like a **practice notebook** — a place where you can make a mess, try new ideas, and break things *on purpose* without worrying about losing your real work.

Obsidian lets you have more than one “vault,” which is just a folder that stores all your notes.
Your main vault is where you keep your real projects, lessons, and data.
Your **sandbox vault** is your test area — it’s like a *training ground* for learning Markdown, trying out plugins, or building layouts before you use them in your main vault.

---

### 🧱 Why Use a Sandbox?

| Reason                 | What It Means                                          |
| ---------------------- | ------------------------------------------------------ |
| **Safe Testing**       | You can experiment without damaging real notes.        |
| **Learn by Doing**     | Try commands, links, and formatting freely.            |
| **Plugin Playground**  | Test features and see what happens.                    |
| **Confidence Booster** | Build your skills before touching your main workspace. |

---

### ⚙️ How to Make One

1. Open Obsidian.
2. Click **“Create New Vault.”**
3. Name it something like **“Sandbox Vault”** or **“Practice Vault.”**
4. Choose a folder on your computer (e.g., Desktop).
5. Click **Create.**

That’s it — you now have a safe zone for learning.

---

### 🧩 How You’ll Use It in This Course

You’ll use your **Sandbox Vault** to:

* Practice Markdown formatting (like `#`, `**bold**`, `[[links]]`)
* Test the PARA templates and lesson menus
* Experiment with linking ideas
* Build confidence before syncing your work into the main **Okee DevOps Vault**

---



### 📁 Copying Folders from a Main Vault to [[sandbox vault]]

If you want to experiment without affecting your main notes, you can **copy folders** into your [[sandbox vault]] for safe testing.

#### 🧭 Step-by-Step Guide

##### 🪟 On Windows / Linux

1. **Open both vault folders** in your file manager:

   * Example paths:

     * Main Vault → `~/Documents/Obsidian/MainVault/`
     * Sandbox Vault → `~/Documents/Obsidian/sandbox vault/`
2. **Select the folders** you want to copy (e.g., `Templates/`, `Projects/`, `Notes/`)
3. **Right-click → Copy**, then **Paste** into your sandbox vault folder
4. Open Obsidian → **[[sandbox vault]]**, and you’ll see the copied folders appear instantly

---

##### 🍎 On macOS

1. Open both vaults in Finder
2. Drag and drop folders while holding **Option (⌥)** to copy instead of move
3. Open Obsidian → **[[sandbox vault]]**, confirm new content appears

---

#### ⚙️ Tip: Use Command Line for Fast Copying

If you prefer the terminal, run:

```bash
## Copy Templates folder from main vault to sandbox vault
cp -r ~/Documents/Obsidian/MainVault/Templates ~/Documents/Obsidian/"sandbox vault"/
```

*(Use quotes if your vault name has spaces.)*

---

#### 🧹 Good Practice

* Keep your **sandbox vault clean** — periodically remove old experiments
* Avoid copying the hidden `.obsidian` folder unless you want to **replicate plugin settings** too
* Rename imported folders (e.g., `Templates_TEST/`) to avoid conflicts

---


### 💬 In Short

> Your sandbox vault is your digital playground — where mistakes are allowed, creativity is encouraged, and you learn by doing.

---
