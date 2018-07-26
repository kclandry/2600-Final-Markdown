# Embedding and Formatting

This page will demonstrate more advanced uses of markdown. Namely, embedding images, using links, creating tables and more. 

---

First of all, on the previous page, there were several horizontal lines used to seperate the individual sections. These were created using groupings of certain symbols. A group of three or more asterisks, dashes(hyphens) , or underscores may be used.

```To demonstrate:
---
*****
___________
```
These become the following lines:

---
*****
___________

In the same vein, throughout this tutorial, I have been demonstrating the use of markdown in plain text, then showing the result of using the text in markdown. This is achieved by framing the section with three tick marks ( \`\ ) This creates a section of code. While this is meant to be used for showing the raw code of programming languages, it works just as well for this tutorial.

***When framed with three tick marks, this sentence will be displayed in plain text.***

```
***When framed with three tick marks, this sentence will be displayed in plain text.***
```

---
One of the most important tools in markdown is the ability to embed links. This functionality has been used to create the links that have jumped you to and from the Table of Contents. Creating links in markdown is, unsurprisingly, simple.

To create a link, frame the word, phrase, sentence or whatever you wish inside a set of square brackets. Follow the closed parentheses with the link inside of parentheses, and markdown will create your link.

```
This is a link to [Google](https://www.google.com/)

[This is also a link to Google](https://www.google.com/)
```

This is a link to [Google](https://www.google.com/)

[This is also a link to Google](https://www.google.com/)

After the link has been finished, placing a word or phrase inside of quotation marks within the parentheses will cause the word or phrase to appear when a user mouses over the link.

```
This is a link to [Google](https://www.google.com/ "Google's Homepage")
```
This is a link to [Google](https://www.google.com/ "Google's Homepage")

If you want to link a page multiple times, it is typically easier to use a referenced link. Instead of placing the link in parentheses each time, place a number within square brackets. Elsewhere in the code, you will define that link.

```
This is a link to [Google][1]
This is also a link to [Google][1]
This is another link to [Google][1]

[1]: https://www.google.com/ "Google's Homepage"
```
This is a link to [Google][1]
This is also a link to [Google][1]
This is another link to [Google][1]

[1]: https://www.google.com/ "Google's Homepage"
---

Images are embedded in similar ways. Follow the same format for creating links, but place an exclamation point before the square brackets to create an embedded image. The text within the square brackets is not seen, it is mostly for users that are visually impaired.

```
![Seagal](http://www.stevensegallery.com/300/300)

![Smaller Seagal](http://www.stevensegallery.com/200/200 "Steven Seagal")
```

![Seagal](http://www.stevensegallery.com/300/300)

![Smaller Seagal](http://www.stevensegallery.com/200/200 "Steven Seagal")

---
The final topic covered on this page will be the use of tables. Tables are excellent ways to organize and present information, and while they can be embedded, tables can be created entirely within markdown. 

Tables are created with vertical lines, most often found on keyboards as the shift-function of the backslash key, typically found above the enter key. By seperating words and phrases into columns using the vertical line ( | ) and creating rows with new lines, making a table in markdown is quite easy. A table is begun by creating header columns and seperating them, and then using three or more dashes in the second row in the same number of columns.

```
Simple|Table|Design
---|---|---
1|2|3
4|5|6

Tables can be formatted within markdown to look nicer within the code.

Simple|Table|Design
------|-----|------
1     |2    |3
4     |5    |6

In the end, they appear the same in markdown.

```
Simple|Table|Design
---|---|---
1|2|3
4|5|6

Tables can be formatted within markdown to look nicer within the code.

Simple|Table|Design
------|-----|------
1     |2    |3
4     |5    |6

In the end, they appear the same in markdown. 

Markdown formatting may be applied as normal within a table. While the header is automatically bolded, by using the same methods as usual, the subjects inside the table may be bolded, italicized or more. By placing colons on the left, right or both sides of the lines in the second row of the code, the columns may be left, right or center justified, respectively. By default, a table's header is centered, while the contents are left justified.

```
Advanced|Table|Design
:------:|----:|:------
**Bolded**|*Italicized*|~~Strikethrough~~
Center Justified    |Right Justified    |Left Justified
```
Advanced|Table|Design
:------:|----:|:------
**Bolded**|*Italicized*|~~Strikethrough~~
Center Justified    |Right Justified    |Left Justified

---

Click [here](../master/Table%20of%20Contents.md) to return to the Table of Contents for this project.

