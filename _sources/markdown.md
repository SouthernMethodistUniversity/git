# Markdown

[The Markdown Guide is a free and open-source reference guide that explains how to use Markdown, the simple and easy-to-use markup language you can use to format virtually any document.](https://www.markdownguide.org/)

## Why use Markdown? 

[Markdown](https://www.markdownguide.org/getting-started/) is a plain text markup format that is easy to read for both computers and humans. This is in contrast to, for example, HTML, which in its unrendered form is not enjoyable for humans to read. Compare the same document in HTML and markdown:

HTML:

```html
<h1>My Book Report</h1>
  <p><i>Persuasion</i> is an <strong>excellent</strong> book that I highly recommend for three reasons:</p>
  <ul>
	<li>It's a comeback story.</li>
	<li>It has a catchy title.</li>
	<li>It's written by Jane Austen.</li>
  </ul>
  <p>You can buy the book <a href="http://www.bookmonopoly.com/persuasion">here.</a></p>
```

Markdown:

```markdown
# My Book Report

*Persuasion* is an **excellent** book that I highly recommend for three reasons:

- It's a comeback story.
- It has a catchy title.
- It's written by Jane Austen.

You can buy the book [here](http://www.bookmonopoly.com/persuasion).
```

When rendered by a browser, both of these documents look identical. However, the markdown document is considerably easier to read in its source form. While HTML is optimized to be readable by the computer, markdown is more balanced between the human and the machine.

### Why Use Markdown?

Markdown is used for a number of reasons:

- It's exportable to other formats, such as HTML, PDF, and GitBook.
- It can be kept under version control—with Git, for example.
- It's rendered automatically on GitHub.
- It can be read locally with a text editor.
- As plain text, it's maintainable.
- It's easy to embed code and images.
- It plays well with the tools we teach at the DRI.

Many of markdown's advantages come from the fact that it's plain text. Tools that work well with code, such as version control, editors, and grep, also work well with markdown.

### Markdown Formatting Guidelines  

Most formatting guidelines here are designed to make markdown source files more readable. Others are designed to preserve semantics, which allow markdown to be rendered the same in different contexts.

Here are some example guidelines.

* Formatting should be as follows:  
1. Separated paragraphs with a blank line.
2. Place blank lines between elements whenever possible. For example, put a blank line between a heading and a paragraph, and between a paragraph and an image link.
3. Use headings consistently, and use them only to denote new sections. For example, do not use headings for emphasis.
  * First header is H1, secondary headers H2, etc. H1 only used at top of page, H2 used to break sections into chunks, H3 only used if necessary within sections that already have an H2.   
  * Compare to outline format:  
  H1 (title of page)  
  H2 (first section)  
  H3 (point 1)  
  H3 (point 2)  
  H3 (point 3)  
  H2 (second section) with no H3 titles necessary  
  H2 (third section)  
  * Are there any extraneous Markdown tags due to errors in coding? (hashtags, dashes, etc.)  
  * [Basic Syntax](https://www.markdownguide.org/basic-syntax/)
4. Use other markdown elements for their intended purpose. Use lists for lists and emphasis for emphasis. For example, do not use emphasis in place of a heading.
5. Unless a raw URL is part of the document, don't leave raw URLs in your document. Incorporate the link into the flow of your prose.
6. If code segments are short, indicate them by indenting. If they're longer, use the ````` syntax.
  * Is coding consistent throughout module?  
7. When introducing new commands or code, put them on a new line so they stand out from the rest of the text.
8. When including [including images,](https://www.markdownguide.org/basic-syntax/#images-1) don't leave the alt text segment `[]` blank. Fill it in with information that would be useful if the image could not be seen or rendered.


