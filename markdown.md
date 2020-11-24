# Markdown Style Guide
This is the style guide for markdown documentation used in the [rcj-sim
project](https://github.com/rcj-sim).
It is based on the guides by [carwin](https://github.com/carwin/markdown-styleguide)
and the [Rocket.Chat project.](https://docs.rocket.chat/contributors/contributing/documentation/markdown-styleguide)

## 1: Formatting of the Markdown Source
### 1.1: Line Length
Lines shall not be longer than eighty (80) characters.
As an exception, links may stand out over the eighty character border.
Tables may be wider than eighty characters, too.

### 1.2: Line Breaks
There shall be a newline after the end of every sentence.
This makes diffs between versions more readable.
A Paragraph break shall be denoted by a single empty line.
There shall be no empty lines at the start of the file.
Lines shall not end with whitespace.
Note that this forbids forced line breaks.
There shall not be multiple consecutive empty lines.

### 1.3: Indentation
Indentation shall not be used in running text.
Tabs shall be used for indentation, not spaces.
For the line limit, a tab counts as four spaces.

## 2: Markup
### 2.1: Headers
Headers shall use the atx style without closing `#` characters.
A single space shall be included before the heading text.
The line of the heading shall start with the first `#`.
Headers should not span more than eighty characters.
Heading levels shall not be skipped.
There shall not be a blank line between a header and the first paragraph.

### 2.2: Emphasis and Inline Code
Bold text shall be denoted with two asterisks.
Italic text shall be denoted with single underscores.
Inline code shall be denoted with single backtics.
There shall not be whitespace between the format specifier (`*`, `_` or
backtick) and the formatted text.

```markdown
**bold text**
_italic text_
`inline code`
```

### 2.3: Horizontal Rules
Horizontal rules should not be used.
Horizontal rules shall be denoted by a paragraph containing three dashes:
`---`

## 3: Lists

```markdown
Example:

- unordered item 1
	1. sub-item 1
	2. second sub-item
- unordered item 2
	line continuation of unordered item 2
```

### 3.1: Tagging
Unordered lists shall use `-` as tags.
Ordered lists shall use ascending numbers as tags.

### 3.2: Indentation
The first level of list shall not be indented.
Sub-lists shall be indented one tab further than their parent.
If an item spans multiple lines, the other lines shall be indented one step
further than their parent.
Note that this means that the starts of the text can be not aligned with each
other.

### 3.3: Paragraph
A list and its sub-lists shall be placed in an own paragraph, separated from
continuous text.

## 4: Blocks
### 4.1: Fenced Code Block Paragraph
A fenced code block shall be placed in its own paragraph.

### 4.2: Fenced Code Block in List
In a list, a fenced code block shall be indented like item text that spans
multiple lines.

### 4.3: Fenced Code Block Language
The programming language of the code listing shall be denoted by a keyword after
the three backticks.

### 4.3: Blockquotes
All lines of a blockquote shall start with a `>` followed by a single space.
Blockquotes should not span multiple paragraphs.

## 5: Tables
### 5.1: Width
Tables may be wider than the 80 character limit.
Table columns shall be as long as the longes cell in the column.
The other cells should be filled with spaces.

### 5.2: Vertical Lines
Vertical lines (pipes) must be used to separate columns.
No vertical lines shall be used at the left and right border of the table.
One space shall be placed before and after the pipe character.

## 6: Hyperlinks
### 6.1: Syntax
The syntax with the link text in `[]` and URL in parentheses shall be used.

### 6.2: File-Relative Links
File-relative links shall be used where possible.

### 6.3: Bare URLs
Bare URLs shall be surrounded by angular brackets.
