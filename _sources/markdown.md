[<<< Previous](pedagogy.md) | [Next >>>](contributing.md)   

# Style Guide 

**See Checklist for Required Content (ADD LINK)**

## Why use Github?
* *link to lesson* etc add text
[Github at SMU](https://www.smu.edu/OIT/Services/GitHub)

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

We use markdown for tutorials for a number of reasons:

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
5. Unless a raw URL is part of the tutorial, don't leave raw URLs in your document. Incorporate the link into the flow of your prose.
6. If code segments are short, indicate them by indenting. If they're longer, use the ````` syntax.
  * Is coding consistent throughout module?  
7. When introducing new commands or code, put them on a new line so they stand out from the rest of the text.
8. When including [including images,](https://www.markdownguide.org/basic-syntax/#images-1) don't leave the alt text segment `[]` blank. Fill it in with information that would be useful if the image could not be seen or rendered.
9. ANYTHING ELSE? do images need to go into image folder? sections into a folder? after certain amount ? (otherwise need to scroll waaaaay down README)



# Jupyter book?
* RULES?
* To be used when: 
  - combining multiple workshops
  - maintained by multiple instructors
  - into a sequence (Research Workshop Path) 
* See example: Repo-[Introduction to TDM](https://github.com/SouthernMethodistUniversity/introTDM) & JB- [IntroTDM](https://southernmethodistuniversity.github.io/introTDM/index.html)

# When to choose Binder or HPC for computational documents 
* RULES?  
* To be used when: 
 - combining multiple computational notebooks 
 - Introductory workshops where familiarity with HPC is not assumed (or required) 
* See example: [Python Repo](https://github.com/SouthernMethodistUniversity/pythonintro)

# Accessability  
* * **HERE..link to accessibility style guide??**
* write accessible documentation (https://developers.google.com/style/accessibility)
* For example do not emphasize text by using color 
[A markdown version emoji cheat sheet](https://github.com/ikatyang/emoji-cheat-sheet). You can call attention using a [geometric icons](https://github.com/ikatyang/emoji-cheat-sheet#geometric) such as :red_circle: or :yellow_circle:

# Attribution
## Free and Open Source Code

In general, it's not necessary to provide in-line citations in the materials for a technical workshop unless you're using someone else's exact prose or you're replicating a significant, non-trivial section of code. For example, code segments found on Stack Overflow do not need to be cited unless you think it's pedagogically helpful. However, if you build your session around replicating a significant portion of a particular application, you must consider the license under which that software is released and consider providing attribution, even if attribution is not required under the terms of the license. In general, free and open source code licenses do not require attribution, but using a large portion of the code may require replicating the license. Check a summary of the terms of the license (or the license itself, if you're feeling adventurous) if you decide to replicate a significant portion of an open-source project in your session.

## Citation practices for workshops

Many of the workshops in this curriculum were created by multiple creators. This makes the process of attributing of each other a bit messy. An interested person can see the precise details what was done and by whom in what order in the GitHub commit log. However, we also realize that folks reading this curriculum may not be Git-literate (yet!) or may access this curriculum as a .PDF or a hard copy document offline. Thus, it is also important to attribute the labor of individual contributors in written form at the beginning of each workshop and every other section of this curriculum. 

Currently, the workshops include two forms of attribution: "Session leader: ..." and "Based on previous work by ..."—the former indicates the person who will be the lead teacher of the workshop during the Summer 2020 DHRI session, and the latter indicates who worked on the content of the workshop. We recognize that both are significant attributions, but that the latter is especially important in terms of citation politics, particularly for students and junior scholars. So, despite its redundancy, we listed a contributors name twice if they both are leading the workshop in June 2018 and if they created or significantly contributed to or revised the workshop's content. It is also of note that various contributors edited the content of each others' workshops.  

In regards to citing other academics, this curriculum aims to follow commonly held academic citation practices, in which direct quotations are formatted and cited as such, and when another scholar's ideas or concepts are referenced, a citation is also included. In general, the following citation information is provided: the author name(s), publication title, and publication date, and a hyperlink to the source, if applicable and within copyright.  

## License?
- Default to CC by SA? discuss



[<<< Previous](pedagogy.md) | [Next >>>](contributing.md)   