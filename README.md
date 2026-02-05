# **Markdown Template Guide**

---

## **Table of Contents**
1. [Introduction](#introduction)
2. [Headers](#headers)
3. [Formatting Text](#formatting-text)
4. [Lists](#lists)
5. [Links and Images](#links-and-images)
6. [Tables](#tables)
7. [Code Blocks](#code-blocks)
8. [Git Commands Section](#git-commands-section)
9. [Conclusion](#conclusion)

---

## **Introduction**
Markdown is a lightweight markup language for creating formatted text using a plain-text editor. This guide covers common Markdown elements and how to use them.

---

## **Headers**
Markdown uses `#` symbols for headers:
```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
**Example:**
# H1
## H2
### H3

---

## **Formatting Text**
1. **Bold:** Use `**Bold**` → **Bold**
2. *Italic:* Use `*Italic*` → *Italic*
3. ~~Strikethrough:~~ Use `~~Strikethrough~~` → ~~Strikethrough~~

---

## **Lists**
### **Unordered List:**
```markdown
- Item 1
- Item 2
  - Sub-item
```
- Item 1
- Item 2
  - Sub-item

### **Ordered List:**
```markdown
1. First Item
2. Second Item
```
1. First Item
2. Second Item

---

## **Links and Images**
```markdown
[Link Text](https://example.com)
![Image Alt Text](https://placehold.co/150)
```
[Link Example](https://example.com)  
![Image Example](https://placehold.co/150)

---

## **Tables**
```markdown
| Column 1 | Column 2 | Column 3 |
|----------|-----------|----------|
| Data 1   | Data 2    | Data 3   |
```

| Column 1 | Column 2 | Column 3 |
|----------|-----------|----------|
| Data 1   | Data 2    | Data 3   |

---

## **Code Blocks**
Inline code: `` `code` `` → `code`

Block of code:
```python
def hello_world():
    print("Hello, world!")
```

---

## **Git Commands Section**
### **Basic Git Commands**
```bash
# Initialize a repository
git init

# Add files to the staging area
git add .
```

---

## **Conclusion**
Markdown is a simple, flexible, and powerful language for creating documents and content. Use this template as a reference or guide for your Markdown projects.

---

### **Markdown Tips:**
- **Bold Text:** `**Bold**`
- *Italic Text:* `*Italic*`
- `Inline Code:` `` `Code` ``
- [Hyperlink Example](https://example.com)
Updated by Jayani as part of Git workshop Task2

# Task 2

### Go to projects directory
```bash
cd C:\Users\JAYANI\Documents\projects
```

### Clone the given repository
```bash
git clone https://github.com/Lexicon-Smaland/Hello-World.git
```

### Enter the cloned repository and and Check the current remote
```bash
cd Hello-World
git remote -v
```
It shows :
```bash
origin  https://github.com/Lexicon-Smaland/Hello-World.git (fetch)
origin  https://github.com/Lexicon-Smaland/Hello-World.git (push)
```

### Create new repo on GitHub, named as "git-workshop-hw" and replace the origin
```bash
git remote set-url origin https://github.com/jayani-athukorala/git-workshop-hw.git
git remote -v
```
Now it shows:
```bash
origin  https://github.com/jayani-athukorala/git-workshop-hw.git (fetch)
origin  https://github.com/jayani-athukorala/git-workshop-hw.git (push)
```

### Modify README.md and commit and push
```bash
Add-Content README.md "Updated by Jayani as part of Git workshop Task2"
git status
git add .\README.md
git commit -m "Update README with Task2 commands"
git push -u origin main
```