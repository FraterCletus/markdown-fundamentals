[[PARA Method]]
[[Lesson 1 Understand Basic Markdown Syntax]]
#### 🧠 #education

###### #learning #training #course #lesson #assessment #resources #project #practice #curriculum #instructional_design #self_study #module
#### ✍️ #markdown

###### #documentation #obsidian #text #writing #formatting #templates #cheatsheet #second_brain #zettelkasten #canvas #organisation #knowledge_management #note_taking #vault #graph_view #dataview #callout #embedding #linking #references #metadata #workflow

| Feature             | Syntax / Example                                       | Output                            |
| ------------------- | ------------------------------------------------------ | --------------------------------- |
| **Heading**         | `# Heading 1`, `## Heading 2`, `### Heading 3`         | Creates titles of decreasing size |
| **Bold**            | `**text**` or `__text__`                               | **text**                          |
| **Italic**          | `*text*` or `_text_`                                   | _text_                            |
| **Bold + Italic**   | `***text***`                                           | _**text**_                        |
| **Strikethrough**   | `~~text~~`                                             | ~~text~~                          |
| **Horizontal Rule** | `---`                                                  | ———                               |
| **Bullet List**     | `- item` or `* item`                                   | • item                            |
| **Numbered List**   | `1. item`                                              | 1. item                           |
| **Task List**       | `- [ ] To do`, `- [x] Done`                            | ✅ interactive checkboxes          |
| **Inline Code**     | `` `code` ``                                           | `code`                            |
| **Code Block**      | `python<br>print("Hello")<br>`                         | Code block                        |
| **Links**           | `[title](https://url.com)`                             | [title](https://url.com/)         |
| **Images**          | `![alt text](image.png)`                               | 🖼️                               |
| **Tables**          | See [[User Experience/Markdown Cheat Sheet#Instant Table]] for syntax. | Markdown-rendered tables          |
###### Instant Table
Copy and paste this
```markdown
|  |  |
| --- |
```

### 🧠 Obsidian Quoting & Embedding Highlights

| **Category**                  | **Feature / Plugin**                                          | **Syntax / Example**                                                                               |
| ----------------------------- | ------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| 🧩 **Core Feature**           | **Full-Note Embed**                                           | `![[NoteTitle]]`                                                                                   |
| 🧩 **Core Feature**           | **Section Embed**                                             | `![[NoteTitle#HeadingName]]`                                                                       |
| 🧩 **Core Feature**           | **Block Embed**                                               | `![[NoteTitle#^blockID]]`                                                                          |
| 🧩 **Core Feature**           | **Quote Block**                                               | `> Quoted text here.`                                                                              |
| 🎨 **Callout Blocks**         | `> [!quote] Text`                                             | Adds stylized callouts for quotes, tips, notes, etc. Can be folded or styled via CSS.              |
| ⚙️ **Note Refactor Plugin**   | _(Context Menu → Extract Selection)_                          | Converts selected text into a new note, replacing it with a link/embed.                            |
| 📚 **Dataview Plugin**        | `dataview\nTABLE FROM #quote`                                 | Collects tagged quotes from across your vault. Perfect for automated quote libraries.              |
| 🧠 **Templater Plugin**       | Use `<% tp.file.include("Note#Heading") %>`                   | Dynamically inserts note sections at template generation time. Great for automating quote imports. |
| 🔗 **Unique Block IDs**       | `Paragraph text ^my-block`                                    | Adds reusable anchors anywhere; allows precise quoting across files.                               |
| 🖌️ **Custom CSS Snippets**   | _(CSS rule for `.internal-embed`)_                            | Modify how embedded content appears (e.g., hide titles, add border, italics).                      |
| 🧮 **Transclusion Chaining**  | `![[NoteA#SectionA]]` inside `NoteB`, then embed `![[NoteB]]` | Allows multi-level embedding — useful for building thematic aggregations.                          |
| 🗂️ **Tag-Driven Collection** | `#quote`, `#source`, `author::`                               | Tag and structure metadata for quotes, searchable and query-ready.                                 |
| 🔍 **Live Updating**          | _(Automatic via embeds)_                                      | Embedded content auto-updates when source is edited — ensuring quote consistency.                  |
