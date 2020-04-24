# Topics

| S.No | Content |
| --------	 | ------------ |
| 1 | [HTML](README.md#html) |
| 2 | [Web Browser](README.md#web-browser) |
| 3 | [Text Editor](README.md#text-editor) |
| 4 | [IDE](README.md#ide) |
| 5 | [Points to Remember](README.md#points-to-remember) |
| 6 | [Common Errors](README.md#common-errors) |
| 7 | [Tag Syntax](README.md#tag-syntax) |
| 8 | [HTML Page Structure](README.md#html-page-structure) |
| 9 | [Element and Attribute](README.md#element-and-attribute) |
| 10 | [Tag Attributes](README.md#tag-attributes) |
| 11 | [Boilerplate code](README.md#boilerplate-code) |
| 12 | [To Type Emojis](README.md#to-type-emojis) |
| 13 | [Inline vs Block Level Elements](README.md#inline-vs-block-level-elements) |
| 14 | [Inline Elements](README.md#inline-elements) |
| 15 | [Block Elements](README.md#block-elements) |
| 16 | [Semantic Tags](README.md#semantic-tags) |
| 17 | [Common Syntax](README.md#common-syntax) |
| 18 | [Plugins](README.md#plugins) |
| 19 | [Documentation References](README.md#documentation-references) |
| 20 | [Tools Reference](README.md#tools-reference) |

# HTML

- Hyper Text Markup Language 
- It is the markup language for creating Web pages and Documents.
- It's not a Programming Language 
- It does not having any Logic.
- HTML is the building block of the any web page. 

# Web Browser

- Web Browser is used to view the HTML.
- Google Chrome
- Mozilla Firefox
- Safari
- Edge
- IE(Please Don't use this)

# Text Editor

- Text Editor is used to write the HTML.
- Sublime Text
- Atom.io
- Visual Studio Code
- Brackets
- Notepad++(Windows)
- TextMate(Mac)

# IDE

- Codepen.io
- atom.io
- https://code.visualstudio.com/

# Points to Remember

- It does not need a Server.
- Files must be end with the .html extension.
- Runs in the Browser.
- index.html is the root/home page of a website.

# Common Errors

- In Windows you could not able to see .html extension -> View -> Options -> View -> Hide extensions for known file types(uncheck).

# Tag Syntax

- Element names surrouned by angle brackets.
- Normally comes in pairs(start tag and end tag)
  ```ruby
  <tagname>content</tagname>
 ```
- Some tags close themselves(i.e)Self closing tag
  ```ruby
  <br>
  ```

# HTML Page Structure

```ruby
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="description" content="HTML Tutorial">
    <title>Document</title>
</head>
<body>
    <h1>This is a heading</h1>
    <p>This is paragraph</p>
</body>
</html>
```
__where,__
- __DOCTYPE html__ indicates the version of HTML.
- __html__ -> indicates this is the html file.
- __head__ -> It holds the information about web page and it tells the browser how to handle the page.
- __title__ -> It defines title of the document.  
- __meta__ -> Meta elements gives extra meta data or associated data to your HTML document. In theis case we tell the broswer when it opens up the file all the text inside our web page is encoded using the UTF-8 encoding system.  
- __meta__ -> Meta data also give information to search engines about the content website.


# Element and Attribute

```ruby
<hr size="3">
```
- where __hr__ is the __HTML element__ and __size="3"__ is the __HTML attribute__.

# Tag Attributes

- Provides information about an element.
- Placed with in the start tag.
- Key/Value pairs(id="someId")

```ruby
<tagname attributename="attributevalue">content</tagname>
```

# Boilerplate code

- It is a unit of writing that can be reused over and over without change.
- In Other words, it's simply a code template which we can reuse.

# To Type Emojis

- On  Mac -> Command + control + space
- On Windows -> Place the cursor in any text field in chrome, Microsoft or Notepad -> WIN + . (or) WIN + ;

# Inline vs Block Level Elements

# Inline Elements

- Do not start on a new line.
- Take only necessary width.
```ruby
<span>, <img>, <a>
```

# Block Elements

- Start on a new line.
- Take full width available.
```ruby
<div>, <h1> - <h6>, <p>, <form>
```
# Semantic Tags

- A Semantic element clearly describes its meaning to both the browser and the Developer.

```ruby
<header></header>
<footer></footer>
<aside></aside>
<main></main>
<artcile></article>
<nav></nav>
<section></section>
<details></details>
```
__where,__
- The header element specifies a header for a document or section.
- The footer element specifies a footer for a document or section.
- The aside element defines some content aside from the content it is placed in (like a sidebar).
- The main element Specifies the main content of a document.
- The article element specifies independent, self-contained content.
- The nav element defines a set of navigation links.
- The section element defines a section in a document.
- Defines additional details that the user can view or hide.


# Common Syntax
| Syntax	 | Descriptions |
| --------	 | ------------ |
| ``` <p> ``` |	paragraph |
| ``` <h1> - <h6> ``` |	Headings |
| ``` <hr> ``` | horizontal rule |
| ``` <br> ``` | single line break |
| ``` <meta> ``` | meta data |
| ``` <li> ``` | list item |
| ``` <ol> ``` | orderd list |
| ``` <ul> ``` | unordered list |
| ``` <th> ``` | header cells |
| ``` <td> ``` | standard cell |
| ``` <thead> ``` | head of the columns |
| ``` <th> ``` | header cells |
| ``` <tr> ``` | table row |
| ``` <tbody> ``` | body content |
| ``` <font> ``` | font face |
| ``` <object> ``` | embedded object |
| ``` <div> ``` | division or a section |
| ``` <form> ``` | form elements |
| ``` <input> ``` | input field |
| ``` <label> ``` | text label |
| ``` <textarea> ``` | input text over multiple rows |
| ``` <blockquote> ``` | section - quoted from another source |
| ``` <a> ``` | Anchor Element |
| ``` <img> ``` | Insert Image |
| ``` <abbr> ``` |  abbreviation or an acronym |
| ``` <cite> ``` | Italic style |


# Plugins

- HTML Boilerplate
- Prettier
- Material Icon Theme

# Documentation References

- https://www.w3schools.com/html/
- https://developer.mozilla.org/en-US/
- https://docs.emmet.io/cheat-sheet/
- https://devdocs.io/html/


# Tools Reference

- web.archive.org (for checking old websites)
- http://www.fileformat.info/info/charset/UTF-8/list.htm (Character List for UTF-8)
- http://www.unicodetables.com/ (for unicode tables) 
- joelonsoftware unicode (for unicode deep Learning).
