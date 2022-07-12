# Markdown Beginner Guide

The README.ms files are big part of the project we make on GitHub because they contain information about the project itself. The md part of the name of the file stands for Markdown and it means that that s the type of the file. The main goal of Markdown is to be easily both written and read. Markdown can also be used to create email.

Visual Studio Code uses the [CommonMark](http://commonmark.org/) Markdown specification.

# Content

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

# Guide
## Headers

Headers are defined by the '#' symbol.

# Heading
<!--  # Heading -->

## Heading
<!--  ## Heading -->

### Heading
<!--  ### Heading -->

#### Heading
<!--  #### Heading -->


## Quotes
Quotes are defined by the '>' symbol.

> Example

## Emphasis

Add emphasis with asterisks '*' and underscores '_'

*Example* 


_Example_ 


## Lists

Create unordered lists using '-', '*', '+' infront the item

- item
* item
+ item

Also you can create sublist by indenting - using tab button

- list
    - sublist
        - another


Create ordered lists just by using number prefix

1. item 1
2. item 2
3. item 3


## Links

Creating a link by surrounding it with angle bracket 

<https://github.com/Krissttina>

To rename a link or to set a custom name to a link you should use '[]' and the wanted text inside and after that the link set in '()' without empry space between

Example: [My project](https://github.com/Krissttina)


## Images

Defining an image is similar to defining a link
In this case you should start with '!' symbol and than put link to the file image

![Git logo](https://d1yjjnpx0p53s8.cloudfront.net/styles/logo-thumbnail/s3/042017/untitled-2_5.png?itok=IlsUnu37)

or you can just refrence it for example: ![name][type]


## Tables
Tables are useful for displaying rows and columns of data. Column headers can be defined in between pipes ' | '. Headers are separated from the table content with a row of dashes ( - ) and pipes ( | ) and there must be at least 3 ashes between each header. The row data follos beneath. 

> **TODO** Create

    Example



The column and row definitions do not have to be at exact same width sizes, but it would be much more readable.

| Header 1 | Header 2 | Header 3 |
| -------- | -------- | -------- |
| Column 1 | Column 2 | Column 3 |
| Column 1 | Column 2 | Column 3 |
| Column 1 | Column 2 | Column 3 |

You also can align the text in a column by using colons ':' in the line breaks between headers and rows. No colon means the default ** left alignment**. Colons one each side signifies **center alignment**. And a trailing colon means **right alignment**.


| Header | Header 1 | Header 2 |
| ------ | :------: | --------: |
| Aligned Left | Aligned Center | Aligned Right | 


# Including code
## Custom HTML

```html
<p>text</p>
```


## Custom CSS

```html
    <style>
        p{
            color: red
        }
    </style>
```

# Tips

Writing a good README

Open a README.md. file in a new project. 

Make sure the file always includes the following elements: 

* Titles and internal titles 
* Introduction - the project's aim 
* Technologies 

Launch 

 
Consider also using additional elements such as:  

- Table of contents 
- Illustrations 
- Scope of functionalities  
- Examples of use 
- Project status  
- Sources 

# Markdown Preview Github Extencion for VS Code
Perfect Extension for VSCode about writing and instantly reviewing the result.

Shortcut: Ctrl + shitf + v -> github pr 