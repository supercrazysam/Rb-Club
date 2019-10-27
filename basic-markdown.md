Too Long, Don't read
[GitHub Flavored Markdown Spec](https://github.github.com/gfm/)

If you can read chinese, read this first then my file
[Markdown 是什么?](https://blog.csdn.net/wirelessqa/article/details/69659073)

I suggest you to read the Raw file first then see this rendered page.

# What is markdown?

Markdown is a lightweight markup language with plain text formatting syntax. Its design allows it to be converted to many output formats, but the original tool by the same name only supports HTML.

You might consider it is something better than MS Word.
In github repository, readme.md is a .md file, which md stands for Markdown.


# Why markdown?

* Support Everywhere
* Easy to learn
* Quick and clean
* Easy On The Eyes
* Sytlish code showcase

# What application should I use for writing markdown?

[I personally recommend Typora (Support Linux, Windows, MacOS](https://www.typora.io/)

[Visual Studio code](https://code.visualstudio.com/)
* If you use vscode, notice you need to install this plugin: [Markdown-all-in-one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)



# Some basic syntax of markdown

[Look At Here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Something Essentials

### Headers

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1
======

Alt-H2
------
```

### Links

```markdown
[I'm an inline-style link](https://www.google.com)
```

### List

```markdown
1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses
```

1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses

### Images / Gifs

```markdown
![alt text](https://images.pexels.com/photos/207962/pexels-photo-207962.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260)
```

![](https://images.pexels.com/photos/207962/pexels-photo-207962.jpeg?auto=compress&cs=tinysrgb&h=750&w=1260)

## Code Expression

### Inline Code

````
  ```javascript
  var s = "JavaScript syntax highlighting";
  alert(s);
  ```
  
  ```python
  s = "Python syntax highlighting"
  print s
  ```
  
  ```
  No language indicated, so no syntax highlighting. 
  But let's throw in a <b>tag</b>.
  ```
````

## Mathematical expression

In markdown, we use Latex if you want to put some fancy  Mathematical expression.

Note that 
* Both Typora and VSCode support Latex syntax.
* Github Flavored Markdown doesn't support Latex syntax.

But We still welcome you guys to use it when needed.

[Syntax Guide](https://katex.org/docs/supported.html)

[Useful Latex Generator](https://latex.codecogs.com/eqneditor/editor.php)

# Tips and Tricks using markdown

## Linking image from your google drive

I strongly recommand uploading the photos on google drive then link it back.

```markdown
![](https://drive.google.com/uc?export=view&id=XXX)
```
Notice here 'XXX' is the ID of the image.

You'll need to grab the ID of the image. Easiest way on the desktop is to right click the file, dive into the Google Drive subcontext menu and choose View on the Web. Grab the string of characters from there and replace the XXX in the code below with it.

## Linking image from imgur


[Imgur](https://imgur.com/)

Upload the image to Imgur then link it back.

## Realtime Preview is very important

[Again, I recommend Typora (Support Linux, Windows, MacOS](https://www.typora.io/)

## Practice your markdown skills online

[Dillinger, The Online Markdown Editor ](https://dillinger.io/)