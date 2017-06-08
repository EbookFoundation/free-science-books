# Contribute to the lists
Hello dear friend, welcome!
This guide details how to contribute to this repository.


## Contributor license agreement
By submitting to this repository you agree to the [CC0](https://creativecommons.org/about/cc0)  [LICENSE](https://github.com/EbookFoundation/free-science-books/blob/master/LICENSE) .


## All the steps you need
1. First of all, what you want to add should be actually 'Free'. Don't mistake "An easy link to Download a book" with "Free".
2. If you don't know how to work with git or github, just simply go to [Wiki: Contribution](https://github.com/vhf/free-programming-books/wiki/Contribution) and read the rest.
3. We have 2 kinds of lists. Make sure you know where you're adding the link:
    
    + **Books** : PDF, HTML, DJVU, ePub, a gitBook.io based site, a Git repo, etc.
    + **Courses** : A course is a well designed learning material which was made by an organized group and is availabe for a long time where there is no interactive tool embeded in the site. e.g.: [OpenCourseWare](http://ocw.mit.edu/), [PHPAcademy](https://phpacademy.org), etc.

4. We prefer small commits rather than one large commit in a pull request. If you don't have the time to make small commit, add an issue with all the links included and we'll add them for you.
5. Use our standard for formatting the .md file. Check it out: [Formatting](#formatting)
6. Must use ***alphabetic*** order.

### Scope
+ If a book would be catalogued in an Library of Congress category other than [Science](http://www.loc.gov/aba/cataloging/classification/lcco/lcco_q.pdf), [Medicine](http://www.loc.gov/aba/cataloging/classification/lcco/lcco_r.pdf), or [Technology](http://www.loc.gov/aba/cataloging/classification/lcco/lcco_t.pdf), for example, ["MUSIC AND BOOKS ON MUSIC"](http://www.loc.gov/aba/cataloging/classification/lcco/lcco_m.pdf) then it's out of scope for this list.
+ If a non-book resource is proposed, for example "screencasts", "interactive tutorials", etc., following the example of [free-programming-books](https://github.com/vhf/free-programming-books/), we encourage these resources to be included in a separate page dedicate to that sort of resource.
+ If a book or resource is a "free-programming" book or resource, it should [go there](https://github.com/vhf/free-programming-books/). Math books might go both places, but not computer science.

### Formatting
+ All lists are `.md` files. Try to learn Github's Markdown syntax. It's simple!
+ All the lists start with an Index, the idea is to show all of sections and subsections there, so it's important to have an index for each section. Right now it's alphabetized, so please use alphabetic order.
+ Sections are using level 3 heading (in HTML is `<h3>`, in Markdown is `###`), and subsections are using level 4 (in HTML is `<h4>`, in Markdown is `####`).

The idea is to have
+ `2` empty lines between last suggested book & new header
+ `1` empty line between header & first book of that very section.
+ `0` empty line between each book in 1 section.
+ `1` empty line at the end of each `.md` file.

Like this example:
```markdown
[...]
* [Essential Pascal Version 1 and 2](http://www.marcocantu.com/epascal/)


### DTrace

* [IllumOS Dynamic Tracing Guide](http://dtrace.org/guide/preface.html)
* [Some Other Book](http://so.me/other/book.html)

BAD : * [IllumOS Dynamic Tracing Guide](http://dtrace.org/guide/preface.html)(PDF)
GOOD: * [IllumOS Dynamic Tracing Guide](http://dtrace.org/guide/preface.html) (PDF)

BAD : * [IllumOS Dynamic Tracing Guide](http://dtrace.org/guide/preface.html)- Robert
GOOD: * [IllumOS Dynamic Tracing Guide](http://dtrace.org/guide/preface.html) - Robert

```

#### What to do about multiple links to the same book ([#1192](https://github.com/vhf/free-programming-books/issues/1192#issuecomment-135969100))
+ if its a different edition, add separate link with a note about its edition
+ if its the same book but in a better format, replace link
+ if one is a webpage and the other is pdf, add separate link with a note about its format

And that's it! Simple, easy and lovely...

We hope you contribute to this great repository. :+1:
