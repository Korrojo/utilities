# Comprehensive Markdown Reference Template

## Table of Contents
01. [Headers](#headers)
02. [Emphasis](#emphasis)
    - [Bold Text](#bold-text)
    - [Italic Text](#italic-text)
    - [Bold and Italic](#bold-and-italic)
    - [Strikethrough](#strikethrough)
03. [Lists](#lists)
    - [Unordered Lists](#unordered-lists)
    - [Ordered Lists](#ordered-lists)
    - [Task Lists](#task-lists)
04. [Links](#links)
    - [URL Links](#url-links)
    - [Image Links](#-mage-links)
        - [Local](#local)
        - [URL](#url)


05. [Blockquotes](#blockquotes)
06. [Code](#code)
    - [Code Blocks](#code-blocks)
    - [Inline Code](#inline-code)
    - [Syntax Highlighting](#syntax-highlighting)
07. [Table](#table)
08. [Horizontal Rule](#horizontal-rule)
09. [Inline HTML](#inline-html)
10. [Escaping Characters](#escaping-characters)
11. [Colored Text (HTML)](#colored-text-html)

## Headers

# H1 - Heading 1
## H2 - Heading 2
### H3 - Heading 3
#### H4 - Heading 4
##### H5 - Heading 5
###### H6 - Heading 6 <br /><br />
## Emphasis

### Bold Text
> **This is bold text**

### Italic Text
> *This is italic text*

### Bold and Italic
> *You **can** combine them*

### Strikethrough
> ~~This is strikethrough text~~ <br /><br />

## Lists

> ### Unordered Lists
* Item 1
* Item 2
  * Item 2a
  * Item 2b

> ### Ordered Lists
1. Item 1
2. Item 2
   1. Sub Item 2.1
   2. Sub Item 2.2
3. Item 3

> ### Task Lists
- [x] This is a complete item
- [ ] This is an incomplete item<br /><br />

## Links

> ### URL Links
[Google](https://www.google.com)

> ### Image Links
> > #### Local

![GitHub Logo](images/github-logo-github-octocat.png) 
<br /><br />

> > #### URL
![GitHub Logo](https://image.pngaaa.com/550/2809550-middle.png)

<br /><br />

## Blockquotes
As Kanye West said:
> We're living the future so
> the present is our past.  

<br />

## Code

> ### Code Blocks
You can use 3 backticks to create a code block:

```java
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
<br />

> ### Inline Code
To denote a word or phrase as inline code, enclose it in backticks (\`). For instance, the word `code` in this sentence is an example of inline code.

<br />

> ### Syntax Highlighting
You can add an optional language identifier to enable syntax highlighting in your fenced code block. For example, to syntax highlight JavaScript code:

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
<br />  

## Table
    You can create tables by assembling a list of words and dividing them with hyphens `-` (for the first row), and then separating each column with a pipe `|`. You can also specify alignment for each column using colons `:`.

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |

<br /> 

## Horizontal Rule
You can create a horizontal rule with three or more of the following:

Hyphens:

---
Asterisks:

***
Underscores:

___

<br />

## Inline HTML 
You can also use raw HTML in your Markdown, and it'll mostly work pretty well.

```html
<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>
</dl>
```
<br />

## Escaping Characters
To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (`\`) in front of the character.

For example, if you want to display an asterisk, you would write `\*`. <br /><br />

## Colored Text (HTML)
Standard Markdown does not support color directly. However, since you can use inline HTML in your Markdown, you can use HTML `span` tags for this purpose. Please note that this might not work in all Markdown parsers.

<span style="color:red;">This is red text.</span>  
<span style="color:green;">This is green text.</span>  
<span style="color:yellow;">This is yellow text.</span>  
<span style="color:blue;">This is blue text.</span>  
<span style="color:white;">This is white text.</span>  
<span style="color:pink;">This is pink text.</span>  
<span style="color:purple;">This is purple text.</span>  
<span style="color:magenta;">This is magenta text.</span>  
<span style="color:orange;">This is orange text.</span>  
