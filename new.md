
# My Markdown Tutorial

Welcome to this tutorial on how to write Markdown! In this guide, we will cover the basics and some extended features of Markdown.

## Adding an Image

To make your content more engaging, you can add images. Here's an example of how to add an image from Unsplash.

![Beautiful Landscape](https://images.unsplash.com/photo-1506748686214-e9df14d4d9d0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzNjUyOXwwfDF8c2VhcmNofDJ8fGxhbmRzY2FwZXxlbnwwfHx8fDE2NDY3MjgyNzQ&ixlib=rb-1.2.1&q=80&w=1080)

## Extended Syntax

Markdown supports several extended features that are not available in plain text. Here are a few examples:

### Tables

Tables are a great way to display data in a structured format.

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

### Task Lists

Task lists are useful for creating to-do lists.

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

### Strikethrough

You can use strikethrough to indicate text that is no longer relevant.

This text has been ~~redacted~~.

## Conclusion

This is a basic introduction to Markdown. Keep practicing and exploring more advanced features to make your documents even better!


# How to Write an HTML Boilerplate

An HTML boilerplate is the basic structure of an HTML document. Here's how to create one.

## Step 1: Doctype Declaration

Start with the doctype declaration to specify the HTML version.

```html
<!DOCTYPE html>



<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!-- Content goes here -->
</body>
</html>


<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

```
# The Anatomy of a CSS Selector

CSS selectors are patterns used to select elements on a web page so you can style them. Understanding CSS selectors is fundamental to mastering CSS. Let's break down the anatomy of a CSS selector.

## Basic Selectors

### Element Selector

The element selector targets all instances of a given HTML element.

```css

p {
    color: blue;
}


.intro {
    font-size: 20px;
}



#header {
    background-color: lightgray;
}

* {
    margin: 0;
    padding: 0;
}


div span {
    color: red;
}


div > p {
    font-weight: bold;
}


div + p {
    margin-top: 10px;
}


div ~ p {
    color: green;
}


a[target] {
    text-decoration: none;
}


input[type="text"] {
    border: 1px solid #ccc;
}



a:hover {
    color: orange;
}


:first-child {
    color: blue;
}


p::first-letter {
    font-size: 2em;
    font-weight: bold;
}


p::before {
    content: "Note: ";
    font-style: italic;
}

```
3. **Save and Preview Your Markdown File**:
   - Save the file as `css-lab.md`.
   - Open the file in a Markdown viewer or editor to preview the formatting and ensure everything looks correct.


# How to Create a File Using the Terminal

Creating files and directories using the terminal is a fundamental skill for any developer. This tutorial will guide you through the basic commands needed to create files and directories on a Unix-based system (like macOS or Linux).

## Opening the Terminal

First, you need to open the terminal application. Here’s how you can do it on different systems:

- **macOS**: Press `Command + Space`, type "Terminal", and press `Enter`.
- **Linux**: Press `Ctrl + Alt + T` or search for "Terminal" in your applications menu.
- **Windows**: Use Git Bash or any Unix-like terminal.

## Navigating the File System

Use the `cd` (change directory) command to navigate through the file system.

```bash

cd ~


cd labs


mkdir projects


cd projects


touch README.md


nano README.md



ls

# Delete the file "sample.txt"
rm ../README.md


rmdir empty_directory

# 
rm -r projects

```
3. **Save and Preview Your Markdown File**:
   - Save the file as `terminal-lab.md`.
   - Open the file in a Markdown viewer or editor to preview the formatting and ensure everything looks correct.



