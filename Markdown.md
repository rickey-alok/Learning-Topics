# Cheat Sheet - MARKDOWN

<!-- TOC -->

- [Cheat Sheet - MARKDOWN](#cheat-sheet---markdown)
- [Headings](#headings)
- [`#H1`](#h1)
  - [`##H2`](#h2)
    - [`###H3`](#h3)
      - [`####H4`](#h4)
        - [`#####H5`](#h5)
          - [`######H6`](#h6)
- [Formatting](#formatting)
- [Emojis](#emojis)
- [List](#list)
  - [Ordered list:](#ordered-list)
  - [Unordered list:](#unordered-list)
  - [Task List:](#task-list)
- [Code](#code)
  - [Inline Code](#inline-code)
  - [Block Code](#block-code)
    - [JSON](#json)
    - [Without Code block defined (ex: JSON)](#without-code-block-defined-ex-json)
- [Links](#links)
  - [External reference](#external-reference)
  - [Internal Reference](#internal-reference)
- [Images](#images)
  - [External reference](#external-reference-1)
  - [Internal Reference](#internal-reference-1)
- [Table](#table)
  - [Alignment](#alignment)
- [Blockquote](#blockquote)
- [Horizontal Rule](#horizontal-rule)
- [Footnote](#footnote)

<!-- /TOC -->

# Headings

# `#H1`

## `##H2`

### `###H3`

#### `####H4`

##### `#####H5`

###### `######H6`

##Custom Heading ID


| Markdown                | HTML                                       | Rendered Output  |
| ----------------------- | ------------------------------------------ | ---------------- |
| `[Heading IDs](#123)` | `<a href="#heading-ids">Heading IDs</a>` | [Heading IDs](#123) |

# Formatting

`Normal`  = Normal

 `**Bold**`  = **Bold**  
 `__Bold__`  = __Bold__

`*Italic*` = *Italic*  
`_Italic_` = _Italic_

`***Bold & Italics***` = ***Bold & Italics***  
`___Bold & Italics___` = ___Bold & Italics___

`Subscript example: H~2~O` = H~2~O

`Superscript example: X^2^` = X^2^

`==Highlight==` = ==Highlight==

`~~Strikethrough~~` = ~~Strikethrough~~

# Emojis

`:joy:` = 😂

`:smile:` = 😄

`:cry:` = 😢

`:tent:` = ⛺️

`:heart:` = ❤️

`:icecream:` = 🍦

`:school:` = 🏫

`:car:` = 🚗

# List

## Ordered list:

Input
```
1. First item
2. Second item
3. Third item
```
Output
1. First item
2. Second item
3. Third item

## Unordered list:
Input
```
- First item
- Second item
- Third item
```
Output
- First item
- Second item
- Third item

## Task List:
Input
```
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
```
Output
- [X] Write the press release
- [ ] Update the website
- [ ] Contact the media

---

Miscellaneous

Input
```
term
: definition
```
Output  

term
: definition


# Code 

## Inline Code


Input
```
`code`
```

Output

`code`

## Block Code

### JSON

Input
~~~
```JSON
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
~~~

Output

```JSON
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
### Without Code block defined (ex: JSON)

Input
~~~
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
~~~

Output
```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```


# Links

## External reference

Input

`[Google](https://www.google.com)` 

Output

[Google](https://www.google.com)

## Internal Reference

Input

`[Linked to readme page](README.md)` 

Output

[Linked to readme page](README.md)

# Images

## External reference

Input

```
![water](https://media.istockphoto.com/photos/underwater-bubbles-picture-id925440650?k=20&m=925440650&s=612x612&w=0&h=OYU-poM2bI0xYJvb8qRAQ5UCc3qvnYt91KNv4nCOjgY=)
``` 

Output

![water](https://media.istockphoto.com/photos/underwater-bubbles-picture-id925440650?k=20&m=925440650&s=612x612&w=0&h=OYU-poM2bI0xYJvb8qRAQ5UCc3qvnYt91KNv4nCOjgY=)



## Internal Reference

Input
```
![water](water.jpg)
``` 

Output

 ![water](Images/water.jpg)

# Table

## Alignment

You can align text in the columns to the left, right, or center by adding a colon `:` to the left, right, or on both side of the hyphens within the header row.



| Syntax                    | Description |            Test Text     |
| :-----------       |    :-------------:   |          ---------------: |
| Text Left------Aligned| Text Center Aligned           | Text Right Aligned       |


# Blockquote

Input
```
> blockquote
```

Output
> blockquote

# Horizontal Rule

Input
```
---
```

Output

---

# Footnote

Input

```
Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.
```

Output

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.