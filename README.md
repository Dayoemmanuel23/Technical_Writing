# Technical_Writing
Sample details of how to be a good technical writer

Writing in **Markdown** is simple and allows you to format text easily. Here’s a quick guide to the basic syntax:

---

### **Basic Markdown Syntax**

#### **1. Headers**
```markdown
# Heading 1  
## Heading 2  
### Heading 3  
#### Heading 4  
##### Heading 5  
###### Heading 6  
```

#### **2. Text Formatting**
- **Bold**: `**bold text**` or `__bold text__` → **bold text**  
- *Italic*: `*italic text*` or `_italic text_` → *italic text*  
- ***Bold & Italic***: `***bold & italic***` → ***bold & italic***  
- ~~Strikethrough~~: `~~strikethrough~~` → ~~strikethrough~~  

#### **3. Lists**
- **Unordered List**:
  ```markdown
  - Item 1
  - Item 2
    - Sub-item (indent with 2 spaces or a tab)
  ```
  - Item 1  
  - Item 2  
    - Sub-item  

- **Ordered List**:
  ```markdown
  1. First item
  2. Second item
     1. Sub-item
  ```
  1. First item  
  2. Second item  
     1. Sub-item  

#### **4. Links & Images**
- **Link**: `[Text](URL)` → [Google](https://google.com)  
- **Image**: `![Alt Text](Image URL)`  
  Example:  
  ```markdown
  ![Markdown Logo](https://markdownlogo.com)
  ```

#### **5. Code & Blockquotes**
- **Inline Code**: `` `code` `` → `code`  
- **Code Block** (with syntax highlighting):
  ````markdown
  ```python
  def hello():
      print("Hello, Markdown!")
  ```
  ````
  Output:
  ```python
  def hello():
      print("Hello, Markdown!")
  ```

- **Blockquote**:  
  ```markdown
  > This is a blockquote.
  > It can span multiple lines.
  ```
  > This is a blockquote.  
  > It can span multiple lines.  

#### **6. Horizontal Line**
```markdown
---
```
Output:  
---

#### **7. Tables**
```markdown
| Syntax      | Description |
|------------|-------------|
| Header     | Title       |
| Paragraph  | Text        |
```
Output:  
| Syntax      | Description |
|------------|-------------|
| Header     | Title       |
| Paragraph  | Text        |

---

### **Example Markdown File**
```markdown
# My Markdown Guide

## Introduction
This is a **Markdown** example.  

### Features
- Easy formatting
- Supports `code` blocks
- Works on GitHub, Reddit, and more

> "Markdown is awesome!" – Me

---
[Learn More](https://www.markdownguide.org)
```

