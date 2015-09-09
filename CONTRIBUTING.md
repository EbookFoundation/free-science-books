# Contribute to the lists
Hello dear friend, welcome! This guide details how to contribute to this repository.

By submitting to this repository you agree to [our license](https://github.com/EbookFoundation/free-science-books/blob/master/LICENSE), which uses [Creative Commons CC0](https://creativecommons.org/about/cc0).


## All the steps you need
1. **First make sure that the link does not already exist in repository.**
2. Only add resources that are _actually free_.
    + Don't mistake a simple "DOWNLOAD" button with "free."
    + Look for an authorized distributor of the resource.
    + Avoid personal storage links (Dropbox, Google Drive) and torrents.
3. If you don't know how to work with git or GitHub, you have several options.
    + Create a [new issue](https://github.com/EbookFoundation/free-science-books/issue) including the resource and link. We will do the rest!
    +  [Fork](https://help.github.com/articles/fork-a-repo) the repo, add new links, and make a [pull request](https://help.github.com/articles/using-pull-requests).
    +  [Just learn GitHub](http://try.github.io/)!
4. We have 2 kinds of lists. Make sure you know where you're adding the link:

    + **Books**: PDF, HTML, DJVU, ePub, a gitBook.io based site, a git repo, etc.
    + **Courses**: Well-designed learning material created by an organized group and made widely available for a long time. May include embedded interactive tools, or require account logins.
      * [MIT OpenCourseWare](http://ocw.mit.edu/)
      * [edX](https://www.edx.org/)

4. We prefer small commits rather than one large commit in a pull request. If you don't have the time to make small commits, add an issue with all the links included and we'll add them for you.
5. Use our standard for formatting the `.md` file. Check it out: [Formatting](#formatting)


### Scope
+ If a book would be catalogued in an Library of Congress category other than [Science](http://www.loc.gov/aba/cataloging/classification/lcco/lcco_q.pdf), [Medicine](http://www.loc.gov/aba/cataloging/classification/lcco/lcco_r.pdf), or [Technology](http://www.loc.gov/aba/cataloging/classification/lcco/lcco_t.pdf), for example, ["MUSIC AND BOOKS ON MUSIC"](http://www.loc.gov/aba/cataloging/classification/lcco/lcco_m.pdf) then it's out of scope for this list.
+ If a non-book resource is proposed, for example "screencasts", "interactive tutorials", etc., following the example of [free-programming-books](https://github.com/vhf/free-programming-books/), we encourage these resources to be included in a separate page dedicate to that sort of resource.
+ If a book or resource is a "free-programming" book or resource, it should [go there](https://github.com/vhf/free-programming-books/). Math books might go both places, but not computer science.

### Formatting
+ All lists are `.md` files. Try to learn Github's Markdown syntax. It's simple!
+ All the lists start with an Index, the idea is to show all of sections and subsections there, so it's important to have an index for each section. Right now it's alphabetized, so please use alphabetic order.
+ Sections are using level 3 heading (in HTML is `<h3>`, in Markdown is `###`), and subsections are using level 4 (in HTML is `<h4>`, in Markdown is `####`).
+ Organize all links in ***alphabetical*** order.

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

* [IllumOS Dynamic Tracing Guide](http://dtrace.org/guide/preface.html) (PDF)
* [Some Other Book](http://so.me/other/book.html) - Robert

```

#### What to do about multiple links to the same book ([#1192](https://github.com/vhf/free-programming-books/issues/1192#issuecomment-135969100))
+ if its a different edition, add separate link with a note about its edition
+ if its the same book but in a better format, replace link
+ if one is a webpage and the other is pdf, add separate link with a note about its format

And that's it! Simple, easy and lovely...

We hope you contribute to this great repository. :+1:
