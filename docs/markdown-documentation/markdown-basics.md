---
title: Markdown Basics
slug: markdown-basics
status: publish
---

# Markdown Basics

## Overview

Markdown is a lightweight markup language used to format plain-text content. It allows contributors to create structured documentation without relying on complex authoring tools.

## 1. Headings

Headings organize information into logical sections.

```markdown
# Heading 1
## Heading 2
### Heading 3
```

Use heading levels sequentially. Avoid skipping levels because this can affect document navigation and accessibility.

## 2. Paragraphs and line breaks

Separate paragraphs with a blank line.

```markdown
This is the first paragraph.

This is the second paragraph.
```

## 3. Text emphasis

Use emphasis to highlight important information.

| Formatting | Markdown syntax | Result |
| --- | --- | --- |
| Bold | `**Important**` | **Important** |
| Italic | `*Note*` | *Note* |
| Inline code | `` `command` `` | `command` |

Use bold formatting sparingly. Avoid using emphasis as a substitute for meaningful headings.

## 4. Lists

### Unordered list

```markdown
- Install the application.
- Open the settings page.
- Select Save.
```

### Ordered list

```markdown
1. Sign in to the application.
2. Open Settings.
3. Select Save.
```

Use numbered lists for sequential procedures and unordered lists for non-sequential information.

## 5. Links

Use descriptive link text rather than generic phrases such as "click here."

```markdown
[GitHub documentation](https://docs.github.com/)
```

## 6. Code blocks

Use fenced code blocks to display commands or examples.

```bash
git clone https://github.com/username/repository.git
```

Specify the language after the opening fence when syntax highlighting is useful.

## 7. Tables

Tables are useful for presenting structured information.

| Element | Purpose |
| --- | --- |
| Heading | Organizes content |
| List | Presents related items |
| Table | Compares structured information |
| Code block | Displays commands or examples |

## Best practices

- Use descriptive headings.
- Maintain consistent formatting.
- Write concise sentences.
- Use lists for scannable information.
- Provide context before showing commands.
- Validate Markdown rendering before publishing.
