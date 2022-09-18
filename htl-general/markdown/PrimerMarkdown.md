# _Markdown_ Primer

## Objective
This document intends to give you an overview of _Markdown_. After an overview of the uses and benefits of _Markdown_ and tools/extensions you can use for writing it, the last section serves as a _showcase_ demonstrating various useful syntax elements - so make sure to check it out!

## History And Benefits Of _Markdown_
The term _markup_ originates from the printing industry, where editors needed to _mark_ their documents for the printer to know how to format it. In computer science _markup languages_ were originally designed for complex tasks (such as _HTML_), and hence were difficult to read for the average human person.

Motivated by the hard readability and complex structure, John Gruber created _Markdown_ in 2004. His goal was to create a _lightweight_ markup language which could be used for writing and formating web documents and was easy to learn for anyone.

Some of the benefits of using _Markdown_ are:
* It doesn't interrupt your workflow by having to use your mouse for changing fonts, creating tables and so on. Everything can be done by keyboard.
* In comparison to _HTML_ you can format your text extremely fast. It's also much more readable in plain-text than _HTML_ or similar markup languages.
* You're not dependening on an operating system or program (such as _Word_) for editing _Markdown_. You can choose whatever editor you like the best (see section _Useful Tools_).
* You have a lot of possibilites for converting or exporting your _Markdown_: You can publish it as _HTML_, _PDF_ and many other formats.
* It's a great way of collaborating, especially with other engineers.

## Useful Tools
While you could write _Markdown_ using the simplest available text editor and simply save it as `.md`-file, there are several editors that will make your life easier.

### _Visual Studio Code_ With Extensions
_Visual Studio Code_ is a great, free choice for writing _Markdown_. It offers you a live preview functionality (see the magnifying glass on the top right when editing `.md`-files). It also offers a lot of extensions for working with _Markdown_, such as:

* [_Markdown PDF_](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf) for exporting to _PDF_. Use _Ctrl+Shift+P_ to open _Visual Studio Code's_ _command palette_ and select _Markdown PDF: Export (pdf)_. Your `.pdf`-file will be generated in the same folder your `.md`-file is in.
* [_Markdown+Math_](https://marketplace.visualstudio.com/items?itemName=goessner.mdmath) for using mathematical formulas in _TeX_-syntax in _Markdown_.
* [_MARP_](https://marp.app/) (_Markdown Presentation Ecosystem_) for creating appealing slides using _Markdown_.
* [_PlantUML_](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml) for creating _UML_ diagrams.

### _MiKTeX_ And _Pandoc_
Using this combination of tools you can generate professionally looking _LaTeX_-style documents. More instructions will be coming soon.

### Other Tools
If you have any other tools you can recommend for writing, previewing or exporting _Markdown_, feel free to expand to this section! Thanks!

## Resources
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
([Archived](https://archive.is/4KYZu))

[Pros And Cons Of Using Markdown For Technical Writing  ](https://hackernoon.com/pros-and-cons-of-using-markdown-for-technical-writing-34f277418a8a) ([Archived](https://archive.is/AEhs0))

---

## _Showcase:_ Overview Of Markdown Syntax
[comment]: <> (This is a comment, that will not be rendered in the document.)
[comment]: <> (The showcase was kindly created by students of the 3AHIF 2021:)
[comment]: <> (Niklas Aichinger, Markus Remplbauer, Darius Pavelescu)

# Headline 1
## Headline 2
---
### Headline 3
---
# Lists
## List 1
- List
- - Subpoint
- - - sub-subpoint

## List 2
* Option 2
* List
* * Sublist

## List 3
+ Option 3
+ List
+ + Sublist

## Ordered List
1. First
2. sdfsdf
3. Second
    1. Third
    2. Sample 1
        1. Sample 2
4. Sample 3

---

# Text

## Text Formating
this is **bold text**. <br> 
this is *cursive bold text* <br>
this is ***cursive bold text***

## Random Text field
```
    This is a text block
```

## Code with language
```
java
public class Main {
    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
    }
}
```
---
# Link
[Duck Duck Go](https://duckduckgo.com) is a great search engine.

---

# Image

## Image 1

![](https://swissfitchick.files.wordpress.com/2013/01/birne.gif)

## Image 2

![Image not found (backup text)](https://invalidaddress.com)

---

# Inline code

The `public` keyword is often used in java.

----

# Blockquotes
> First one
>> Second
>>> Third

---

# Math

Use the _Markdown+Math_-extension to write mathematical formulas in your documents. An inline example would be $A \implies B$ with single `$`s, but you can also use `$$` to make your formulas stand out:

$$A \land B \lor C \equiv \neg D \implies E$$
$$\underline{\forall x: \exists y: isMarkdown(x, y)}$$
$$\therefore G$$