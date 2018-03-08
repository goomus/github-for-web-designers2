Github for Web Designers
========================

Hi! Welcome to the companion reference to my lynda.com Github for Web Designers course. This reference also serves as the exercise files for my course, so you can download the exercise files from this repo as well.

## [View the companion reference site](https://github.com/goomus/github-for-web-designers2)


###  other change

Turndown Demo
=============

This demonstrates [turndown](https://github.com/domchristie/turndown) – an HTML to Markdown converter in JavaScript.

Usage
-----

    var turndownService = new TurndownService()
    console.log(
      turndownService.turndown('<h1>Hello world</h1>')
    )

* * *

It aims to be [CommonMark](http://commonmark.org/) compliant, and includes options to style the output. These options include:

*   headingStyle (setext or atx)
*   horizontalRule (*, -, or _)
*   bullet (*, -, or +)
*   codeBlockStyle (indented or fenced)
*   fence (` or ~)
*   emDelimiter (_ or *)
*   strongDelimiter (** or __)
*   linkStyle (inlined or referenced)
*   linkReferenceStyle (full, collapsed, or shortcut)