# Markdown Tutorial

## Italics and Bold

_italic_

**bold**

**_bold and italic_**

## Headers

# Header one
## Header two
### Header three
#### Header four
##### Header five
###### Header six

## Links

### Inline Link

[decription text in sqaure brackets and URL in parentheses] (www.google.com)

The Latest News from [the BBC](www.bbc.com/news)

### Reference Link

Here's [a link to something else][another place].
     Here's [yet another link][another-link].
     And now back to [the first link][another place].

     [another place]: www.github.com
     [another-link]: www.google.com

## Images

### Inline Image Link

![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png)

### Reference Image

[Black cat][Black]

[Orange cat][Orange]

[Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg

[Orange]:http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png


## Blockquotes

 A blockquote is a sentence or paragraph that's been specially formatted to draw attention to the reader.

 To create a block quote, all you have to do is preface a line with the "greater than" caret (>). For example:

> "In a few moments he was barefoot, his stockings folded in his pockets and his
  canvas shoes dangling by their knotted laces over his shoulders and, picking a
  pointed salt-eaten stick out of the jetsam among the rocks, he clambered down
  the slope of the breakwater."

If your quote spans multiple paragraphs, use the `>` on each line

> His words seemed to have struck some deep chord in his own nature. Had he spoken
of himself, of himself as he was or wished to be? Stephen watched his face for some
moments in silence. A cold sadness was there. He had spoken of himself, of his own
loneliness which he feared.
>
> —Of whom are you speaking? Stephen asked at length.
>
> Cranly did not answer.

## Lists

### Unordered Lists

* Milk
* Eggs
* Salmon
* Butter

### Ordered Lists

1. Crack three eggs over a bowl
2. Pour a gallon of milk into the bowl
3. Rub the salmon vigorously with butter
4. Drop the salmon into the egg-milk bowl

### Sub Lists

* Calculus
    * A professor
    * Has no hair
    * Often wears green
* Castafiore
    * An opera singer
    * Has white hair
    * Is possibly mentally unwell

## Paragraphs

### Soft Breaks

Do I contradict myself?··
Very well then I contradict myself,··
(I am large, I contain multitudes.)


Each dot ( · ) represents a space on the keyboard.

## Tables

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

### Alignment

You can align text in the columns to the left, right, or center by adding a colon (:) to the left, right, or on both side of the hyphens within the header row.

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |


# Fenced Code Blocks

The basic Markdown syntax allows you to create code blocks by indenting lines by four spaces or one tab. If you find that inconvenient, try using fenced code blocks. Depending on your Markdown processor or editor, you’ll use three backticks  or three tildes (~~~) on the lines before and after the code block. The best part? You don’t have to indent any lines!

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```


### Syntax Highlighting 

  ```html

<p>this is a test</p>
```

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## Footnotes

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

## Definition Lists

Some Markdown processors allow you to create definition lists of terms and their corresponding definitions. To create a definition list, type the term on the first line. On the next line, type a colon followed by a space and the definition.

First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

## Strikethrough

You can strikethrough words by putting a horizontal line through the center of them. The result looks like this. This feature allows you to indicate that certain words are a mistake not meant for inclusion in the document. To strikethrough words, use two tilde symbols (~~) before and after the words.

~~The world is flat.~~ We now know that the world is round.

## Task Lists

Task lists allow you to create a list of items with checkboxes. In Markdown applications that support task lists, checkboxes will be displayed next to the content. To create a task list, add dashes (-) and brackets with a space ([ ]) in front of task list items. To select a checkbox, add an x in between the brackets ([x]).

- [x] Write the press release
- [ ] Update the website
- [ ] Do some other stuff

## Emojis

Gone camping! :tent: Be back soon.

That is so funny! :joy:

## Disabling automatic urls

`www.example.com`


