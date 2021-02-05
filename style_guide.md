View this page in RAW format to see the corresponding Markdown. This project requires Python 3 and [the mkdocs static site generator][mkdocs].

[mkdocs]:https://www.mkdocs.org/user-guide/writing-your-docs/#writing-with-markdown

# Title Case for One Main Page Heading

## Initial case for all sub-headings on page

_italics_ and _Book names_

"Article names" (straight quotes)

## Code

Use inline code marks for:

* `file names`
* `Unix commands`
* `inline code`
* `Class.classMethod()`
* `[Class]#instanceMethod()`

Use fenced code blocks for any command line examples.

## Admonitions
!!! note "Optional title"
    This is an admonition. The Cinder theme currently supports `note`, `warning`, and `danger` admonition types.

## Images
Images **shall** have an alt-text and title. Use this link style for images.

```markdown
![alt text][logo]
[logo]: URL "title"
```

## Key terms
Use **both** bold and italics to identify the main entry for key terms. The definition of any key term should immediately follow.

It's important to remember _**complex name**_.

## Abbreviations
Any abbreviations that may be new or unfamiliar should clarified using Markdown. The build tool (mkdocs) will automatically add the appropriate HTML.

*[HTML]: Hyper Text Markup Language

# Highlights
This ==highlights== or ==marks== certain content.

# Footnotes
This line has a footnote.[^fn] Within Markdown, the reference should go near where it's called. The build tool (mkdocs) will organize the footnotes at the bottom of the page.

At the end of any page with footnotes,
    #### Footnotes
    ///Footnotes Go Here///

[^fn]: Footnote footer

# Tables
Simple tables can use the built-in Markdown syntax. For anything complicated, it's probably best to move directly to HTML.
