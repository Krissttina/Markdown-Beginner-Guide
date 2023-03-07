# Markdown Beginner Guide

## Table of Contents

- [Intro](#intro)
- [Guide](#guide)
    - [Headers](#headers)
    - [Quotes](#quotes)
    - [Emphasis](#emphasis)
    - [Links](#links)
    - [Lists](#lists)
    - [Images](#images)
    - [Tables](#tables)
- [Including code](#including-code)
    - [Custom HTML](#custom-html)
    - [Custom CSS](#custom-css)
- [Tips](#tips)

## Intro

The README.md files are big part of the projects on GitHub because they contain information about the project itself. The "md" part of the file name stands for "Markdown" since that's the type of the file.

Visual Studio Code uses the [CommonMark](http://commonmark.org/) Markdown specification.
## Guide
### Headers

Headings are defined by the '#' symbol. In order to work properly between the symbol and the title text should have space. 
The count of the symbols defines the font size. One is the biggest and as many as you put as smaller they become.

# Heading
<!--  # Heading -->

## Heading
<!--  ## Heading -->

### Heading
<!--  ### Heading -->

#### Heading
<!--  #### Heading -->

### Quotes

Quotes are defined by the '>' symbol followed by the text.

> Example

### Emphasis

Add emphasis with asterisks '*' or underscores '_'.

*Example* 

_Example_ 

### Lists

You can create unordered lists using '-', '*' or '+' symbol in front of the item.

- item
* item
+ item

You can also create sublist by indenting - using TAB button.

- list
    - sublist
        - another

<!-- - list
    - sublist
        - another -->

Or create ordered lists just by using number prefix.

1. item 1
2. item 2
3. item 3

### Links

Creating a link is done by surrounding the text with angle brackets:

<https://github.com/Krissttina>

<!-- <https://github.com/Krissttina> -->

To rename a link or to set a custom name to a link you should use '[]' (where you put the name you want to call the link) and immediatly after that the link set in '()'. Note: There should not be space between them.

    Example: [My project](https://github.com/Krissttina) -> the link is exactly the same

### Images

Defining an image is similar to defining a link. In this case you should start with '!' symbol and than put "[]" within them put some name (this name won't be visible). Finally put the link to the file image in bracets '()'.

![Git logo](https://d1yjjnpx0p53s8.cloudfront.net/styles/logo-thumbnail/s3/042017/untitled-2_5.png?itok=IlsUnu37)

or you can just reference it for example: ![name](image path)


### Tables

Tables are useful for displaying rows and columns of data. Column headers can be defined in between pipes "|". Headers are separated from the table content with a row of dashes "-" and pipes "|" and there must be at least 3 ashes between each header. The row data follows beneath. 


The column and row definitions don't have to be exactly the same width, but this way it will be more readable.

| Header 1 | Header 2 | Header 3 |
| -------- | -------- | -------- |
| Column 1 | Column 2 | Column 3 |
| Column 1 | Column 2 | Column 3 |
| Column 1 | Column 2 | Column 3 |

You can also align the text in a column by using colons ':' in the line breaks between headers and rows. No colon means the default ** left alignment**. Colons on each side signifies **center alignment**. And a trailing colon means **right alignment**.


| Header | Header 1 | Header 2 |
| ------ | :------: | --------: |
| Aligned Left | Aligned Center | Aligned Right | 

### Other

To underline text it should be surrounded by "**" symbols without spaces.

> **TODO** Example

To create this effect just add TAB in front of the text.

    Example

## Including code
### Custom HTML

In order to include html code in the md file you should use the following technique.

```html
<p>text</p>
```

 - The example is in the brackets.

[```html
<p>text</p>
``` ]

## Custom CSS

The technique with the CSS code is the same.

```html
    <style>
        p{
            color: red
        }
    </style>
```

## Tips

### Tips for writing a good README

1. Open a README.md file in a new project. 

2. Make sure the file always includes the following elements: 

    * Titles and internal titles 
    * Introduction 
        * The project's aim 
    * Technologies 
        * Used to build the project
    * Table of contents 
        * To make navigation through the md easier
    * Illustrations  
    * Examples of use   
    * Sources 

## Markdown Preview Github Extension for VS Code

Perfect Extension for VSCode about writing and instantly reviewing the result.

    Markdown Preview Github Styling

Shortcut: Ctrl + shitf + v
