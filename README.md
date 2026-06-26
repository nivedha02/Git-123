# Markdown Headings (README Notes)

## What are headings?

Headings are used to organize and structure a document. They create a hierarchy of sections, making the content easier to read and navigate.

## Heading Syntax

```markdown
# Heading 1 (H1)
## Heading 2 (H2)
### Heading 3 (H3)
#### Heading 4 (H4)
##### Heading 5 (H5)
###### Heading 6 (H6)
```

## Heading Levels

| Markdown | HTML   | Purpose                    |
| -------- | ------ | -------------------------- |
| `#`      | `<h1>` | Main title of the document |
| `##`     | `<h2>` | Major section              |
| `###`    | `<h3>` | Subsection                 |
| `####`   | `<h4>` | Sub-subsection             |
| `#####`  | `<h5>` | Lower-level heading        |
| `######` | `<h6>` | Lowest heading level       |

## Default Sizes (Browser)

| Heading | Font Size        |
| ------- | ---------------- |
| H1      | 2em (≈32px)      |
| H2      | 1.5em (≈24px)    |
| H3      | 1.17em (≈18.7px) |
| H4      | 1em (≈16px)      |
| H5      | 0.83em (≈13.3px) |
| H6      | 0.67em (≈10.7px) |

> **Note:** These are the default browser sizes. Platforms like GitHub, VS Code, and Notion may use different styles.

## Headings vs Normal Text

| Heading                                                         | Normal Text                 |
| --------------------------------------------------------------- | --------------------------- |
| Defines the structure of the document                           | Used for regular content    |
| Bold and larger by default                                      | Normal font size and weight |
| Rendered as `<h1>`–`<h6>`                                       | Rendered as `<p>`           |
| Improves readability and navigation                             | Contains the body content   |
| Helps search engines and screen readers understand the document | Has no heading semantics    |

## Best Practices

* Use only one **H1 (`#`)** as the document title.
* Follow headings in order (`H1 → H2 → H3`) whenever possible.
* Use clear and descriptive heading names.
* Avoid skipping heading levels unless there is a good reason.
* Keep headings short and meaningful.

## Example

```markdown
# Markdown Guide

## Introduction
Basic overview of Markdown.

## Syntax

### Headings
How to create headings.

### Lists
How to create ordered and unordered lists.
```
