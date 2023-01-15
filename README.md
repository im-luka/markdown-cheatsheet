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
9. [Tables](#tables)
10. [Task List](#tasklist)
11. [Footnote](#footnote)
12. [Heading ID](#headingid)
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
