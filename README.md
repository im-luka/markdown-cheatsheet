# ⬇️ The Only Markdown Cheatsheet You Need

_You can find PDF & images cheatsheet. Feel free to download and use it.  
You can also follow docs below:_

#### ⚠️ Note
Everything listed here is about GitHub Markdown.  
I've also written some articles about Markdown in general with more features.  


---

### What is Markdown?
Markdown is a lightweight markup language that you can use to format plain text documents.  
Write docs for your GitHub project, edit your GitHub profile _README_ etc. You fill find it all here.  
Let's dive into it.

#### Table of Contents

1. [Paragraph](#paragraph)
2. [Headings](#headings)
3. [Emphasis](#emphasis)
4. [Blockquote](#blockquote)
5. [Images](#images)
6. [Links](#links)
7. [Code](#code)
8. [Lists](#lists)
    - [Ordered List](#orderedlist)
    - [Unordered List](#unorderedlist)
    - [Mixed List](#mixedlist)
9. [Table](#table)
10. [Task List](#tasklist)
11. [Footnote](#footnote)
12. [Jump to section](#sectionjump)
13. [Horizontal Line](#horizontalline)
14. [HTML](#html)

---

<a name="paragraph" />

## Paragraph
By writing regular text you are basically writing a paragraph.

```
This is a paragraph.
```
This is a paragraph.

---

<a name="headings" />

## Headings
There are 6 heading variants. The number of "#" symbols, followed by text, indicates the importance of the heading.

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

---

<a name="emphasis" />

## Emphasis
Modifying text is so neat and easy. You can make your text bold, italic and strikethrough.

```
Using two asterisks **this text is bold**.  
Two underscores __work as well__.  
Let's make it *italic now*.  
You guessed it, _one underscore is also enough_.  
Can we combine **_both of that_?** Absolutely.
What if I want to ~~strikethrough~~?
```

Using two asterisks **this text is bold**.  
Two underscores __work as well__.  
Let's make it *italic now*.  
You guessed it, _one underscore is also enough_.  
Can we combine **_both of that_?** Absolutely.  
What if I want to ~~strikethrough~~?

---

<a name="blockquote" />

## Blockquote
Want to emphasise importance of the text? Say no more.

```
> This is a blockquote.
> Want to write on a new line with space between?
>
> No problem at all. 
> PS. you can **style** your text _as you want_.
```

> This is a blockquote.
> Want to write on a new line with space between?
>
> No problem at all. 
> PS. you can **style** your text _as you want_.

---

<a name="images" />

## Images
The best way is to simply drag & drop image from your computer directly. You can also create reference to image and assign it that way.  
Here is the syntax.

```
![text if the image fails to load](auto-generated-path-to-file-when-you-upload-image "Text displayed on hover")

[logo]: auto-generated-path-to-file-when-you-upload-image "Hover me"
![error text][logo]
```

![text if the image fails to load](https://user-images.githubusercontent.com/46372998/212541682-9907aaea-5198-45a9-8961-2acc8a98a0db.png "Text displayed on hover")

[logo]: https://user-images.githubusercontent.com/46372998/212541682-9907aaea-5198-45a9-8961-2acc8a98a0db.png "Hover me"
![error text][logo]

---

<a name="links" />

## Links
Similar to images, links can also be inserted directly or by creating a reference. You can create both inline and block links.

```
[markdown-cheatsheet]: https://github.com/im-luka/markdown-cheatsheet
[docs]: https://github.com/adam-p/markdown-here

[Like it so far? Follow me on GitHub](https://github.com/im-luka)
[My Markdown Cheatsheet - star it if you like it][markdown-cheatsheet]
Find some great docs [here][docs]
```

[markdown-cheatsheet]: https://github.com/im-luka/markdown-cheatsheet
[docs]: https://github.com/adam-p/markdown-here

[Like it so far? Follow me on GitHub](https://github.com/im-luka)  
[My Markdown Cheatsheet - star it if you like it][markdown-cheatsheet]  
Find some great docs [here][docs]

---

<a name="code" />

## Code
You can cerate both inline and full block code snippets. You can also define programming language you were using in your snippet. All by using backticks.

```
    I created `.env` file at the root.

    ```
    {
      learning: "Markdown",
      showing: "block code snippet"
    }
    ```

    ```js
    const x = "Block code snippet in JS";
    console.log(x);
    ```
```

I created `.env` file at the root.

```
{
  learning: "Markdown",
  showing: "block code snippet"
}
```

```js
const x = "Block code snippet in JS";
console.log(x);
```

---

<a name="lists" />

## Lists
As you can do in HTML, Markdown allows creating of both ordered and unordered lists.

<a name="orderedlist" />

### Ordered List

```
1. HTML
2. CSS
3. Javascript
4. React
5. I'm Frontend Dev now 👨🏼‍🎨
```

1. HTML
2. CSS
3. Javascript
4. React
5. I'm Frontend Dev now 👨🏼‍🎨

<a name="unorderedlist" />

### Unordered List

```
- Node.js
- Express
- Nest.js
- Learning Backend ⌛️
```

- Node.js
- Express
- Nest.js
- Learning Backend ⌛️

<a name="mixedlist" />

### Mixed List
You can also mix both of the lists and create sublists.  
**PS.** Try not to create lists deeper than two levels. It is the best practice.

```
1. Learn Basics
   1. HTML
   2. CSS
   3. Javascript
2. Learn One Framework
   - React 
     - Router
     - Redux
   - Vue
   - Svelte
```

1. Learn Basics
   1. HTML
   2. CSS
   3. Javascript
2. Learn One Framework
   - React 
     - Router
     - Redux
   - Vue
   - Svelte

---

<a name="table" />

## Table
Great way to display well-arranged data. Use "|" symbol to separate columns and ":" symbol to align row content.

```
| Left Align (default) | Center Align | Right Align |
| :------------------- | :----------: | ----------: |
| React.js             | Node.js      | MySQL       |
| Next.js              | Express      | MongoDB     |
| Vue.js               | Nest.js      | Redis       |
```

| Left Align (default) | Center Align | Right Align |
| :------------------- | :----------: | ----------: |
| React.js             | Node.js      | MySQL       |
| Next.js              | Express      | MongoDB     |
| Vue.js               | Nest.js      | Redis       |

---

<a name="tasklist" />

## Task List
Keeping track of the tasks that are done, and those that need to be done.

```
- [x] Learn Markdown
- [ ] Learn Frontend Development
- [ ] Learn Full Stack Development
```

- [x] Learn Markdown
- [ ] Learn Frontend Development
- [ ] Learn Full Stack Development

---

<a name="footnote" />

## Footnote
Want to describe something at the end of the file? Use footnote!

```
#### I am working on a new project. [^1]
[^1]: Stack is: React, Typescript, Tailwind CSS  

Project is about music & movies.
```

#### I am working on a new project. [^1]
[^1]: Stack is: React, Typescript, Tailwind CSS  

Project is about music & movies.

##### Hope you will like it. [^see]
[^see]: Loading... ⌛️

---

<a name="sectionjump" />

## Jump to section
You can give ID to a section so that you can jump straight to that part of the file from wherever you are.

```
[Jump to a section with custom ID](#some-id)

...

<a name="some-id" />

##### Section with some ID
```

[Jump to a section with custom ID](#some-id)

---

<a name="horizontalline" />

## Horizontal Line
You can use asterisks, hyphens or underlines (*, -, _) to create horizontal line.  
The only rule is that you must include at least three chars of the symbol.

```
First Horizontal Line

***

Second One

-----

Third

_________
```

First Horizontal Line

***

Second One

-----

Third

_________


---

<a name="html" />

## HTML
You can also use raw HTML in your Markdown file. Most of the times that will work well, but sometimes you can experience some differences that you are not used to when working with standard HTML. Using CSS will not work.

```
<h1>This is a heading</h1>
<p>Paragraph...</p>

<hr />

<img src="auto-generated-path-to-file-when-you-upload-image" width="200">
<a href="https://github.com/im-luka">Follow me on GitHub</a>

<br />
<br />

<p>Quick hack for <strong><em>centering image</em></strong>?</p>
<p align="center"><img src="auto-generated-path-to-file-when-you-upload-image" /></p>
```


<h1>This is a heading</h1>
<p>Paragraph...</p>

<hr />

<img src="https://user-images.githubusercontent.com/46372998/212544874-d0654588-82f7-44f2-bbfa-2bf85fd73854.png" width="200">
<a href="https://github.com/im-luka">Follow me on GitHub</a>

<br />
<br />

<p>Quick hack for <strong><em>centering image</em></strong>?</p>
<p align="center"><img src="https://user-images.githubusercontent.com/46372998/212544874-d0654588-82f7-44f2-bbfa-2bf85fd73854.png" width="200" /></p>

---

<a name="some-id" />

##### Section with some ID
