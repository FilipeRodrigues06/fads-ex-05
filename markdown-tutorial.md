# Markdown tutorial

A dummy document to demonstrate the basic Markdown formatting syntax.
Exercise 5 of Fundamentals of Agro-Environmental Data Science.

## 1. Titles (headings)

Titles are set with the cardinal character `#`. The number of cardinals defines
the level of the title.

# This is a main (first level) title

## This is a second level title

### This is a third level title

## 2. Emphasis

The following four words **are in bold typeface**, but the rest are not.

The following four words *are in italic typeface*, but the rest are not.

To cite someone else's text, use a blockquote:

> text blockquote

## 3. Lists

Ordered list:

1. Item one
2. Item two
3. Item three

Unordered (bulleted) list:

- Item one
- Item two
- Item three

## 4. Code

This sentence has `this portion of code` inline.

And this is a block of code:

```python
def printMyName(name):
   a = name
   print(a)
```

## 5. Links and images

[Markdown Guide](https://www.markdownguide.org/)

![Logo do ISA](./images/LogoISA.jpg)

The image path is relative to this file: `./` is the directory where
`markdown-tutorial.md` is, `images` is a subdirectory of it, and `LogoISA.jpg`
is the image file inside that subdirectory.

## 6. Tables

Columns are separated with `|`, and `---` goes below the row with the column
headings:

|ID| Column 1| Column 2| Column 3|
|--|---------|---------|---------|
|1 | item 1  | item 2  | item 3  |
|2 | item 4  | item 5  | item 6  |

## Wrap up

In this exercise, I used the very basics of Markdown: headings, bold and italic
type faces, blockquotes, lists, inline code and code blocks, links, images and
tables.

# References

[1] https://daringfireball.net/projects/markdown/syntax

[2] https://www.markdownguide.org/cheat-sheet/
