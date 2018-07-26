# Advanced Markdown

This section will cover some of the more complex features of markdown. These are functions that are less commonly used, but are valuable to know, as when the situation arises, they are quite useful. Some of these functionalities are coded in ways similar to HTML or SVG, which markdown has (limited) support for.

---

Collapsible sections of text are useful for reducing clutter in a page when dealing with large amounts of text. A collapsible section begins and ends with the 'details' header. The summary denotes what the section will display when collapsed, while the section following that is what is contained inside. 

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

Images, like most of markdown, are by default left-aligned. However, an image can be aligned to the center or the right. To align an image to the right, one must use the following code, defining the width and height (in pixels) of the image.

```
<img align="right" width="200" height="300" src="http://www.stevensegallery.com/200/300">
```

<img align="right" width="200" height="300" src="http://www.stevensegallery.com/200/300">

To align an image to the center is a little more involved. You have to define a paragraph using the \<p> tag, and align that to the center.










```
<p align="center">
  <img width="500" height="300" src="http://www.stevensegallery.com/500/300">
</p>
```
<p align="center">
  <img width="500" height="300" src="http://www.stevensegallery.com/500/300">
</p>

Images in markdown are created in-line by default, allowing text to flow around it.

---
