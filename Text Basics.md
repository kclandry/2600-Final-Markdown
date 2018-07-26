# Markdown Basics: Text Formatting
#### This page will cover the basics of simple text formatting. It will include making text italicized, bold and more.

The first step to creating markdown in github is to ensure when you are creating a new file, to use the file extension ".md". This tells github that you are making a markdown file. Forgetting to do this will make the file appear as raw text. If you are having this issue, be sure that your file is called "file.md" and not just "file". 

***

### Headers

The formatting that will be often used first in a markdown document is, appropriately, headers. Headers are denoted with the # pound sign. Placing additional pound symbols creates different, and smaller, headers. The biggest and next-biggest headers can be denoted with a line of five = equal signs or - dashes under the text, respectively.


```To demonstrate:

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

Header 1
=====

Header 2
-----
```
That section becomes this cascading formatting:

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

Header 1
=====

Header 2
-----

---

### Emphasizing Text

Emphasizing text in markdown is both simple and modular. You can affect **single** words, **multiple words** or whole paragraphs. Every type of formatting has a symbol or symbols that you use to denote its use. You will type the symbol when you want to start the formatting, then again when it is done.

Italics are denoted by a single asterisk or a single underscore. * or _

Bold is denoted with a double asterisk or double underscore. ** or __

Three underscores or asterisks combines the two, creating bolded italics. *** or ___

To create strikethrough text, frame your words with two tildes. ~~


```To demonstrate:

You can use a single *asterisk* or _underscore_ to italicize words, a double **asterisk** or 
double __underscore__ to make something     bolded, and two ~~tildes~~ to make something strikethrough. 
You can use ***three asterisks*** or ___three underscores___ to get bolded   italics. 
You can use these functions within each other as well. *By using a single asterisk, 
this whole sentence is italicized, but by   putting **two asterisks here**, that part is bolded as well.*
```

With markdown, that paragraph turns into this:

You can use a single *asterisk* or _underscore_ to italicize words, a double **asterisk** or double __underscore__ to make something bolded, and two ~~tildes~~ to make something strikethrough. You can use ***three asterisks*** or ___three underscores___ to get bolded italics. You can use these functions within each other as well. *By using a single asterisk, this whole sentence is italicized, but by putting **two asterisks here**, that part is bolded as well.*

***

### Blockquotes

The next type of basic formatting is the "blockquote". Using the > key, one can create quoted text. A second > creates an indented quote.

```To demonstrate:

>This is a blockquote
>>Two symbols indents the quote. This is often used for quoting someone within your original quote.
```

That section becomes this:


>This is a blockquote
>>Two symbols indents the quote. This is often used for quoting someone within your original quote.

***

### Lists

The other basic type of text formatting is the use of lists. Lists can be either ordered (numbered) or unordered. 

Simply put, using a number followed by a period, you create a numbered list. Using a single, unclosed asterisk, a minus (-) or a plus (+), you can create an unordered list. These types of lists can be combined freely.

```To demonstrate:

1. This
2. Creates
3. An ordered list

* This
- Creates
+ An unordered list

They may be combined:

1. This is the start of an ordered list
2. Unordered lists may be placed within it
    * Use the same methods as above
    * To make unordered additions
            * You can indent them to created a "nested" list
3. And return to the ordered list at any time
```

Markdown turns the above text into the following:


1. This
2. Creates
3. An ordered list

* This
- Creates
+ An unordered list

They may be combined:

1. This is the start of an ordered list
2. Unordered lists may be placed within it
    * Use the same methods as above
    * To make unordered additions
            * You can indent them to created a "nested" list
3. And return to the ordered list at any time

---

Click [here](../master/Table%20of%20Contents.md) to return to the Table of Contents for this project.

