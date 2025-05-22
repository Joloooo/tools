


| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |




Task Lists

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media




# Comprehensive Markdown Syntax Reference

## Headings

# H1
## H2
### H3
#### H4
##### H5
###### H6

---

## Emphasis

*Italic text*  
_Italic text_

**Bold text**  
__Bold text__

***Bold and Italic***  
___Bold and Italic___

---

## Strikethrough

~~This text is strikethrough~~

---

## Blockquotes

> This is a blockquote.

>> Nested blockquote

---

## Lists

### Unordered List

- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
- Item 3

### Ordered List

1. First item
2. Second item
   1. Nested item 1
   2. Nested item 2
3. Third item

### Task Lists

- [x] Completed task
- [ ] Incomplete task

---

## Code

### Inline Code

`Inline code snippet`

### Code Blocks

```javascript
console.log("Hello, Markdown!");
```

### Syntax Highlighting

```python
def greet():
    print("Hello, Markdown!")
```

---

## Horizontal Rules

---

***

___

---

## Links

[Visit OpenAI](https://openai.com)

### Reference Style Links

[OpenAI][website]

[website]: https://openai.com

---

## Images

![Alt text](https://example.com/image.png "Image Title")

### Image Reference

![Example Image][logo]

[logo]: https://example.com/image.png

---

## Tables

| Syntax | Description |
|--------|-------------|
| Header | Title       |
| Paragraph | Text     |

---





## Escaping Characters

\*Literal asterisks\*

\_Literal underscores\_

---

## Line Breaks

First line  
Second line

---

## Emoji

:smile: :+1: :rocket:

---

## Footnotes

Here's a sentence with a footnote.[^1]

[^1]: This is the footnote.

---

## Collapsible Section

<details>
<summary>Click to expand</summary>

Hidden content here.

</details>

---

## Superscript and Subscript

Superscript: X<sup>2</sup>  
Subscript: H<sub>2</sub>O

---

## Highlighting (not supported everywhere)

==Highlighted text==

---

## Definition Lists

Term 1
: Definition 1

Term 2
: Definition 2

---

## Checklist with nested items

- [ ] Task A
  - [x] Subtask A1
  - [ ] Subtask A2
- [x] Task B

---

## Badge (GitHub style)

![Badge](https://img.shields.io/badge/label-message-blue)

---

## Alignment in Tables

| Left | Center | Right |
| :--- | :----: | ----: |
| Text | Text   | Text  |

---

## HTML within Markdown

<div style="color:blue;">This text is blue</div>

---

## Auto-linking URLs

https://openai.com

---

## Mention Users or Teams (GitHub)

@username

---

## Video Embeds (HTML)

```html
<video controls>
  <source src="movie.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
```

---

## Audio Embeds (HTML)

```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
```

---

---
## Json strings 
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

---


## Markdown Comment (hidden so it is actually not displayed )

<!-- This is a comment -->

---

## Markdown YAML Front Matter

```yaml
---
title: "Sample Document"
author: "OpenAI"
---
```

---

## Markdown mathematical expressions (LaTeX supported on GitHub)

Inline math: $E=mc^2$

Block math:

$$
\int_{0}^{\infty} x^2 \,dx
$$

---

## Table of Contents (auto-generated in GitHub)


```markdown
## Table of Contents
- [Section 1](#section-1)
- [Section 2](#section-2)
```

---

## Page Anchor (link to section)

[Go to top](#comprehensive-markdown-syntax-reference)

