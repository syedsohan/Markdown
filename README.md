<p align="center"><img src="./images/Markdown-Logo.png" alt="Markdown-Logo" width="400"/></p>

# Markdown and GFM (GitHub Flavoured Markdown) Crash Course 2021

Markdown provides a powerful yet straightforward way for users (both technical and non-technical) to write plain text documents that can be rendered richly as HTML.


## Table of contents

  - [What is Markdown?](#what-is-markdown)
  - [What is GFM?](#what-is-gfm)
  - [Headings](#headings)
  - [Headings Alternate Syntax](#headings-alternate-syntax)
  - [Paragraphs](#paragraphs)
  - [Line Breaks](#line-breaks)
  - [Emphasis](#emphasis)
  - [Bold](#bold)
  - [Italic](#italic)
  - [Bold and Italic](#bold-and-italic)
  - [Blockquotes](#blockquotes)
  - [Blockquotes with Multiple Paragraphs](#blockquotes-with-multiple-paragraphs)
  - [Nested Blockquotes](#nested-blockquotes)
  - [Blockquotes with Other Elements](#blockquotes-with-other-elements)
  - [Lists](#lists)
  - [Ordered Lists](#ordered-lists)
  - [Unordered lists](#unordered-lists)
  - [Adding Elements in Lists](#adding-elements-in-lists)
  - [Code](#code)
  - [Code Blocks](#code-blocks)
  - [Images](#images)
  - [Horizontal Rules](#horizontal-rules)
  - [Links](#links)
  - [Escaping Characters](#escaping-characters)
  - [Tables](#tables)
  - [Fenced Code Blocks](#fenced-code-blocks)
  - [Syntax Highlighting](#syntax-highlighting)
  - [Heading IDs](#heading-ids)
  - [Strikethrough](#strikethrough)
  - [Task Lists](#task-lists)
  - [Collapsible Items](#collapsible-items)
  - [Badges](#badges)
  - [Emoji](#emoji)
  - [Automatic URL Linking](#automatic-url-linking)
  - [Disabling Automatic URL Linking](#disabling-automatic-url-linking)

## What is Markdown?

Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like `#` or `*`.

You can use Markdown most places around GitHub:

  - Gists
  - Files with the `.md` or `.markdown` extension.

## What is GFM?

GitHub.com uses its own version of the Markdown syntax that provides an additional set of useful features, many of which make it easier to work with content on GitHub.com.

Note that some features of **GitHub Flavored Markdown** are only available in the descriptions and comments of **Issues** and **Pull Requests**. These include **@mentions** as well as references to **SHA-1 hashes, Issues, and Pull Requests**. Task Lists are also available in Gist comments and in Gist Markdown files.

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Headings 

To create a heading, add number signs (#) in front of a word or phrase. The number of number signs you use should correspond to the heading level. For example, to create a heading level two `(<h2>)`, use three number signs (e.g. `##` My Header).
 # Heading 1
 ## Heading 2
 ###### Heading 6

```md
# Heading 1
## Heading 2
###### Heading 6
```

## Headings Alternate Syntax

Alternatively, on the line below the text, add any number of `==` characters for heading level 1 or `--` characters for heading level 2.

Heading 1
===============
Heading 2
---------------
```md
Heading level 1
===============

Heading level 2
---------------
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Paragraphs

To create paragraphs, use a blank line to separate one or more lines of text.

```md
To create paragraphs, use a blank line to separate one or more lines of text.

To create paragraphs, use a blank line to separate one or more lines of text.
```

## Line Breaks

To create a line break `(<br>)`, end a line with two or more spaces, and then type return.

```md
This is the first line.  
And this is the second line.
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Emphasis

You can add emphasis by making text bold or italic.
  ## Bold

  - Hello **World**.
  - Hello __World__.
  - Hello **World**!
  
  ## Italic

  - Hello *World*.
  - Hello _World_.
  - Hello *World*!
  
  ## Bold and Italic

  - Hello ***World***.
  - Hello ___World___.
  - Hello --*World--*.

```md
## Bold

- Hello **World**.
- Hello __World__.
- Hello **World**!

## Italic

- Hello *World*.
- Hello _World_.
- Hello *World*!

## Bold and Italic

- Hello ***World***.
- Hello ___World___.
- Hello --*World--*.
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Blockquotes
To create a blockquote, add a `>` in front of a paragraph.

> Hello, World!
  
  ## Blockquotes with Multiple Paragraphs
  
  Blockquotes can contain multiple paragraphs. Add a `>` on the blank lines between the paragraphs.

  > Hello, World!
  >
  > Ramadan Mubarak.

  ## Nested Blockquotes

  Blockquotes can be nested. Add a `>>` in front of the paragraph you want to nest.

  > Hello, World!
  >
  >> Ramadan Mubarak.


  ## Blockquotes with Other Elements

  Blockquotes can contain other Markdown formatted elements.

  > Hello, **World**!
  >
  >> ***Ramadan Mubarak***.


```md
## Blockquotes

> Hello, World!
  
## Blockquotes with Multiple Paragraphs

> Hello, World!
>
> Ramadan Mubarak.

## Nested Blockquotes

> Hello, World!
>
>> Ramadan Mubarak.

## Blockquotes with Other Elements

> Hello, **World**!
>
>> ***Ramadan Mubarak***.
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Lists

You can organize items into ordered and unordered lists.

  ## Ordered Lists

  To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

  1. One
  2. Two
  
  <div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

  ## Unordered lists
  To create an unordered list, add dashes `(-)`, asterisks `(*)`, or plus signs `(+)` in front of line items. Indent one or more items to create a nested list.

  - One
  - Two

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

  ## Adding Elements in Lists

  To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab.

  - One
  - Two
    
    Three
  
  - Four

```md
## Ordered Lists

1. One
2. Two
  
## Unordered lists

- One
- Two

## Adding Elements in Lists

- One
- Two

    Three

- Four
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Code

To denote a word or phrase as code, enclose it in backticks **(`)**.

At the command prompt, type `touch`.

```md
## Code

At the command prompt, type `touch`.
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Code Blocks

Code blocks are normally indented **four spaces or one tab**. When they’re in a list, indent them **eight spaces or two tabs**.

1. Open the file.
2. Find the following code block on line 298:

        <html>
          <head>
            <title>Hello, World!</title>
          </head>

3. Update the title to match the name of your website.

```md
## Code Blocks

1. Open the file.
2. Find the following code block on line 298:

        <html>
          <head>
            <title>Hello, World!</title>
          </head>

3. Update the title to match the name of your website.
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Images

1. Open the folder containing the Markdown Logo.

    ![Markdown Logo](./images/logo.png "Markdown")

2. Close the folder.


```md
## Images

Format: ![Alt Text](url)

1. Open the folder containing the Markdown Logo.

    ![Markdown Logo](./images/logo.png "Markdown")

2. Close the folder.
```

## Horizontal Rules

To create a horizontal rule, use three or more asterisks `(***)`, dashes `(---)`, or underscores `(___)` on a line by themselves.

---

You got it right!

```md
## Horizontal Rules

---

You got it right!
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Links

To create a link, enclose the link text in brackets (e.g., [GitHub]) and then follow it immediately with the URL in parentheses (e.g., (https://github.com/)).

I love [GitHub](https://github.com/)

<!-- Adding Titles -->
I love [GitHub](https://github.com/ "GitHub")

<!-- URLs and Email Addresses -->

<https://github.com>

<test@test.com>

<!-- Formatting Links -->

I love ***[GitHub](https://github.com/ "GitHub")***

See the section on [`Links`](#links).

```md
## Links

I love [GitHub](https://github.com/)


<!-- Adding Titles -->

I love [GitHub](https://github.com/ "GitHub")


<!-- URLs and Email Addresses -->

<https://github.com>

<test@test.com>

<!-- Formatting Links -->

I love ***[GitHub](https://github.com/ "GitHub")***

See the section on [`Links`](#links).
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Escaping Characters

To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash `(\)`in front of the character.

You can use a backslash to escape the following characters:

**(\,`,*,_,,{ },[ ],< >,( ),#,+,-,.,!,|)**

\- Without the backslash, this would be a bullet in an unordered list.

```md
## Escaping Characters

\- Without the backslash, this would be a bullet in an unordered list.
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Tables

To add a table, use three or more hyphens `(---)` to create each column’s header, and use pipes `(|)` to separate each column. You can optionally add pipes on either end of the table.


You can align text in the columns to the left, right, or center by adding a colon `(:)` to the left, right, or on both side of the hyphens within the header row. **Cell widths can vary. The rendered output will look the same.**

| **Name**      | **Age**     | **Country**   |
| :---          |    :----:   |          ---: |
| John          | 46          | Seychelles    |
| Kevin         | 56          | Kazakhstan    |

---
Build a table using the graphical interface, and then copy the generated Markdown-formatted text into your file. [Markdown Tables Generator](https://www.tablesgenerator.com/markdown_tables "Markdown Tables Generator")


```md
## Tables

| **Name**      | **Age**     | **Country**   |
| :---          |    :----:   |          ---: |
| John          | 46          | Seychelles    |
| Kevin         | 56          | Kazakhstan    |
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Fenced Code Blocks

The basic Markdown syntax allows you to create code blocks by indenting lines by four spaces or one tab, but sometimes it is a hectic one to do. So by using fenced code blocks we can get rid of it. Three backticks (```) or three tildes (~~~) on the lines before and after the code block will do the work for you.

```
{
  "firstName": "John",
  "lastName": "Cena",
  "age": 44
}
```

```md
## Fenced Code Blocks

    ```
    {
      "firstName": "John",
      "lastName": "Cena",
      "age": 44
    }
    ```
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Syntax Highlighting

Many Markdown processors support syntax highlighting for fenced code blocks. This feature allows you to add color highlighting for whatever language your code was written in. To add syntax highlighting, specify a language next to the backticks before the fenced code block.

```php
{
  $firstName = "John";
  $lastName = "Cena";
  $age = 25;
}
```

```md
## Syntax Highlighting

    ```php
    {
      $firstName = "John";
      $lastName = "Cena";
      $age = 25;
    }
    ```
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Heading IDs

To add a custom heading ID, enclose the custom ID in curly braces on the same line as the heading.

You can link to headings with custom IDs in the file by creating a standard link with a number sign (#) followed by the custom heading ID.

[Heading IDs](#heading-ids)

```md
## Heading IDs

[Heading IDs](#heading-ids)
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Strikethrough

This feature allows you to indicate that certain words are a mistake not meant for inclusion in the document. To strikethrough words, use two tilde symbols `(~~)` before and after the words.

~~Hello Wprld~~! Hello World!

```md
## Strikethrough

~~Hello Wprld~~! Hello World!
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Task Lists

Task lists allow you to create a list of items with checkboxes. To create a task list, add dashes `(-)` and brackets with a space `([ ])` in front of task list items. To select a checkbox, add an x in between the brackets `([x])`.

- [x] Learn Markdown.
- [ ] Practice Markdown.
- [ ] Repeat It.

```md
## Task Lists

- [x] Learn Markdown.
- [ ] Practice Markdown.
- [ ] Repeat It.
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

##  Collapsible Items

Content can be collapsed using HTML’s `<details>` and `<summary>` tags.

<details>
<summary>Click this to collapse.</summary>
<ol style="line-height:180%">
  <li>Dhaka</li>
  <li>Dinajpur</li>
  <li>Chittagong</li>
</ol>
</details>

```md
##  Collapsible Items

<details>
<summary>Click this to collapse.</summary>
<ol style="line-height:180%">
  <li>Dhaka</li>
  <li>Dinajpur</li>
  <li>Chittagong</li>
</ol>
</details>
```

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Badges

Browse [Shields Io](https://shields.io/) a complete list of badges and locate a particular badge by using the search bar or by browsing the categories. Click on the badge to fill in required data elements for that badge type (like your username or repo) and optionally customize (label, colors etc.). And it's ready for use!

Use the button at the bottom to copy your badge url or snippet, which can then be added to places like your GitHub readme files or other web pages.

![Badge](https://img.shields.io/badge/Language-Markdown-lightgrey)

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Emoji

There are two ways to add emoji to Markdown files: copy and paste the [emoji](https://emojipedia.org/) into your Markdown-formatted text, or type emoji shortcodes.

That is so funny! 😂

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Automatic URL Linking

That means if you type http://www.example.com, your Markdown processor will automatically turn it into a link even though you haven’t used brackets.

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## Disabling Automatic URL Linking

If you don’t want a URL to be automatically linked, you can remove the link by denoting the URL as code with backticks.

`http://www.example.com`

```md
## Disabling Automatic URL Linking

`http://www.example.com`
```
<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## License

[MIT](https://choosealicense.com/licenses/mit/)

  

---

<div align="center">
Copyright &copy; 2021 <b><a href="https://github.com/syedsohan ">@syedsohan</a></b>
</div>

<div align="right">
    <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>
