# Markdown Samples

# Headings

# h1

## h2

### h3

#### h4

##### h5

###### h6

## Lists

ul - using -

- item 1
- item 2
  - item 2-1
  - item 2-2
- item 3

OR - ul using \*

- item 1
- item 2

OR - ul using +

- item 1
- item 2

ol - list

1. item 1
2. item 2
   1. item 2-1
   2. item 2-2
3. item 3

## Paragraphs

Writing normal text is straight forward. You just type it out.
If you press enter once the following text is added on to what you just typed.

If you press enter twice then you get a new paragraph with a line space between them.  
If you want a new paragraph without the line space between them then put two spaces at the end of the paragraph before it.

## Bold Text

The text that you want to make **bold has 2\* before and after the text**. Or you can use a **double \_underscore before and after to bold the text**.

## Italic Text

The text that you want to make _italic has 1\* before and after the text_. Or you can use a _single \_underscore before and after to bold the text_.  
To make text **_both bold and italic_** you surround the text with 3\*, or **_3 \_underscores_**.

## Highlight

To <mark>highlight text</mark> use the html tag \<mark\>.

## Subscript and Superscript

Use the html tags \<sub\> and \<sup\> to provide subscript H<sub>2</sub>O and superscript X<sup>2</sup>.

## Emojis

The easiest way to place emojis into your text is to copy and paste them in😊.  
Windows key + . displays emojis 😎👴🍕

## Code Blocks

Surround the text that you want to be code with a backtick \` for example `this is monospace font`

For multiline code use a triple backtick \```  
Adding \'js\' after the three ticks adds coloring that shows javascript code.

```js
//This is a comment
const x = 37;
let y = 38;
let funct = function () {
  console.log("Some text!");
};
```

```c#
//C# code
int x = 45;
string w = "This is a string.";
```

## Links

You place the text for the link in [] brackets and then the actual link in \( \) brackets.
[This text is a link](https://google.com)
If you want the text to be the actual link then put the link inside angle brackets. <https:\google.com>

## Images

Images have the same format as links except you put a ! exclamation character before the square brackets. The text inside the square brackets becomes the alt text for the image. The link in the \( \) brackets is the source of the image.

## Blockquotes

Start with an \> angle bracket and a space then your text plus 2 spaces for a new line.  
You can put 2 or 3 angle brackets to get more indent.

> Some Text  
> More Text
>
> > Like this with 2 \>
> >
> > > Or like this with 3 \>

## Horizontal Rule

You have to have at least 3 of - or \_ or \*. Dashes seem to be preferable.

---

## Tables - Available in Extended Markdown

Left align put colon to the left of the dash line.  
Right align put colon to the left of the dash line.
Center align put colon before and after dash line
| Col 1 | Col 2 | Col 3 |
| :----- | ------: | :----: |
| This | is | a |
| table | that | has |
| three | columns | and is |
| left | right | center |

## Checklists - Available in Extended Markdown

- [ ] This is an unchecked checkbox
- [x] This is a checked checkbox
