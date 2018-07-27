# Advanced Markdown

This section will cover some of the more complex features of markdown. These are functions that are less commonly used, but are valuable to know, as when the situation arises, they are quite useful. Some of these functionalities are coded in ways similar to HTML or SVG, which markdown has (limited) support for.

--- 
### Collapsible Sections

Collapsible sections of text are useful for reducing clutter in a page when dealing with large amounts of text. A collapsible section begins and ends with the 'details' header. The "summary" denotes what the section will display when collapsed, while the text following  is what is contained inside. A collapsible section is opened or closed by clicking on the "summary" header.

```
<details>
<summary>Collapsible Section</summary>
You can write whatever you want here. It will appear as normal when the section is opened.
However, no other markdown formatting works here. Only plain text will appear here, everything else
will have had its formatting removed.
</details>
```
<details>
<summary>Collapsible Section</summary>
You can write whatever you want here. It will appear as normal when the section is opened.
However, no other markdown formatting works here. Only plain text will appear here, everything else
will have had its formatting removed.
</details>

---
### Sizing Images

Github supports the use of HTML, and using that, we can have greater control over image sizes and alignments. Instead of using the standard markdown image insertion code, instead use the HTML ```<img>``` tag. The image then is defined to have a height and width, as well as a title.

```
<img src="http://www.stevensegallery.com/500/500" height="500" width="500" title="Steven the Musician">
```

<img src="http://www.stevensegallery.com/500/500" height="500" width="500" title="Steven the Musician">

An image can be stretched or squished to fit a specific height or width. This will create distortion and is genreally best to be avoided. 
```
<img src="http://www.stevensegallery.com/500/500" height="200" width="500" title="Steven the Musician">
```

<img src="http://www.stevensegallery.com/500/500" height="200" width="500" title="Steven the Musician">
---
### Aligning Images
Images, like most of markdown, are by default left-aligned. However, an image can be aligned to the center or the right. To align an image to the right, one must use the following code, defining the width and height (in pixels) of the image.

```
<img align="right" width="200" height="300" src="http://www.stevensegallery.com/200/300">
```

<img align="right" width="200" height="300" src="http://www.stevensegallery.com/200/300">

To align an image to the center is a little more involved. You have to define a paragraph using the \<p> tag, and align that to the center.


```
<p align="center">
  <img width="400" height="350" src="http://www.stevensegallery.com/400/350">
</p>
```
<p align="center">
  <img width="400" height="350" src="http://www.stevensegallery.com/400/350">
</p>

Images in markdown are created in-line by default, allowing text to flow around it. This image has centered in the space left from the picture to the right. If we enter the code again, without an image to the right, it centers properly.

<p align="center">
  <img width="400" height="350" src="http://www.stevensegallery.com/400/350">
</p>


---
### Task Boxes

Github has a special "flavored" markdown that has some features that not everwhere that uses markdown offers. Firstly, Github markdown offers support for task lists. With special formatting, they appear with boxes (checked or unchecked) next to them.

```
* [x] Think about doing the thing
* [ ] Talk about doing the thing
* [ ] Do the thing
```

* [x] Think about doing the thing
* [ ] Talk about doing the thing
* [ ] Do the thing

These sorts of things are useful for lists individually, but also when working in groups. Github is a version control system, designed to help teams work together. These sorts of lists assist in keeping everyone abreast of the progress of a project.

---

### Direct Mentions (@)

In line with begin a version control system, Github offers a way to directly mention another user. by typing the "@" symbol, followed with the username of the individual or team, the subject will recieve a notification directing them to the location. This is useful when working with groups on projects on Github.

---

### Emoji

Lastly, and perhaps least, Github, along with some other markdown-using websites and services, support emojis. These small images will likely have limited usefulness, but it is worth knowing nonetheless. An emoji is created by placing the appropriate emoji code within a pair of colons. 

```
:sunglasses: :8ball: :whale: :eight: :six: :seven: :five: :three: :zero: :nine:
```
:sunglasses: :8ball: :whale: :eight: :six: :seven: :five: :three: :zero: :nine:

A full list of the emojis that Github supports can be found [here.](http://www.emoji-cheat-sheet.com "Github Emojis")

---

### Footnotes (Not supported in Github)

There are several more markdown functions, such as definitions and footnotes. However, these functions of markdown are not supported by Github and cannot be demonstrated here. In other places that do support these functions, they work similarly to other forms of reference.

A footnote is created in the same way a link or image reference is created, but uses a caret ( ^ ) to turn it into a footnote. When you define the reference, the document creates the footnote at the bottom of the page, and links the note to and from the origination point. 

A sentence with a footnote[^5] in it would have a footnote. It would be elsewere defined as [5] as normal, and show at the bottom of the page. 

However, Github does support HTML. By using the HTML superscript tag (```<sup></sup>```), we are able to simulate a footnote. 

```
This is an example of a footnote<sup>1</sup>.

```
This is an example of a footnote<sup>1</sup>.

After this, you must place the footnote manually at the bottom of the page. While this doesn't offer the same convenience as a normal footnote, it is all that can be done in Github. 

---

### Definitions (Not supported in Github)

A definition is also a reference based function. It is created independant of the initial reference, however. With links, images and footnotes, a reference is created and defined elsewhere. With a definition, the initial reference is not used. A definition is denoted with an asterisk before the square brackets. Once defined, whenever the word used within the brackets is used in the document, the definition is displayed if the user hovers over the word. This is used mostly for abbreviations.

*[URL]: Uniform Resource Locator

With this definition, whenever URL is typed, the word is automatically defined.

---

Click [here](../master/Table%20of%20Contents.md) to return to the Table of Contents for this project.
