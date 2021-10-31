# Contribute to the lists
Hello dear friends, welcome!
This guide details how to contribute to this repository.


## Contributor license agreement
By submitting to this repository you agree to the [CC0](https://creativecommons.org/about/cc0)  [LICENSE](https://github.com/EbookFoundation/free-science-books/blob/master/LICENSE) .


## All the steps you need
1. First of all, what you want to add should be actually 'Free'. Don't mistake "An easy link to Download a book" with "Free".
2. If you don't know how to work with git or github, just simply go to [Wiki: Contribution](https://github.com/vhf/free-programming-books/wiki/Contribution) and read the rest.
3. We have 2 kinds of lists. Make sure you know where you're adding the link:
    
    + **Books** : PDF, HTML, DJVU, ePub, a gitBook.io based site, a Git repo, etc.
    + **Courses** : A course is a well-designed learning material which was made by an organized group and is available for a long time where there is no interactive tool embedded in the site. e.g.: [OpenCourseWare](http://ocw.mit.edu/), [PHPAcademy](https://phpacademy.org), etc.

4. Make sure to follow the [guidelines below](#guidelines) and respect the [Markdown formatting](#formatting) of the files.

5. Travis CI will run tests to make sure your lists are alphabetized and formatting rules are followed. Be sure to check that your changes pass the tests.

### Guidelines
- make sure a book is free. Double-check if needed. It helps the admins if you comment in the PR as to why you think the book is free
- we don't accept files hosted on Google Drive, Dropbox, Mega, Scribd, Issuu and other similar file upload platforms
- insert your links in alphabetical order. If you see a misplaced link, please reorder it and submit a PR
- use the link with the most authoritative source (meaning author's website is better than editor's website is better than third party website)
    + no file hosting services (this includes (but is not limited to) Dropbox and Google Drive links)
- always prefer a `https` link over a `http` one -- as long as they are on the same domain and serve the same content
- on root domains, strip the trailing slash: `http://example.com` instead of `http://example.com/`
- always prefer the shortest link: `http://example.com/dir/` is better than `http://example.com/dir/index.html`
    + no URL shortener links
- usually prefer the "current" link over the "version" one: `http://example.com/dir/book/current/` is better than `http://example.com/dir/book/v1.0.0/index.html`
- if a link has an expired certificate/self-signed certificate/SSL issue of any other kind:
  1. *replace it* with its `http` counterpart if possible (because accepting exceptions can be complicated on mobile devices)
  2. *leave it* if no `http` version but link still accessible through `https` by adding an exception to the browser or ignoring the warning
  3. *remove it* otherwise
- if a link exists in multiple formats, add a separate link with a note about each format
- if a resource exists at different places on the Internet
    + use the link with the most authoritative source (meaning author's website is better than editor's website is better than third party website)
    + if they link to different editions, and you judge these editions are different enough to be worth keeping them, add a separate link with a note about each edition
- prefer atomic commits (one commit by addition/deletion/modification) over bigger commits. No need to squash your commits before submitting a PR. (We will never enforce this rule as it's just a matter of convenience for the maintainers)
- if the book is older, include the publication date with the title. 
- include the author name or names where appropriate. You can shorten author lists with "et al."

### Scope
+ If a book would be catalogued in the Library of Congress category other than [Science](http://www.loc.gov/aba/cataloging/classification/lcco/lcco_q.pdf), [Medicine](http://www.loc.gov/aba/cataloging/classification/lcco/lcco_r.pdf), or [Technology](http://www.loc.gov/aba/cataloging/classification/lcco/lcco_t.pdf), for example, ["MUSIC AND BOOKS ON MUSIC"](http://www.loc.gov/aba/cataloging/classification/lcco/lcco_m.pdf) then it's out of scope for this list.
+ If a non-book resource is proposed, for example "screencasts", "interactive tutorials", etc., following the example of [free-programming-books](https://github.com/vhf/free-programming-books/), we encourage these resources to be included in a separate page dedicate to that sort of resource.
+ If a book or resource is a "free-programming" book or resource, it should [go there](https://github.com/vhf/free-programming-books/). Math books might go both places, but not computer science.

### Formatting
+ All lists are `.md` files. Try to learn [Markdown](https://guides.github.com/features/mastering-markdown/)  syntax. It's simple!
+ All the lists start with an Index, the idea is to show all the sections and subsections there, so it's important to have an index for each section. Right now it's alphabetized, so please use alphabetic order.
+ Sections are using level 3 heading (in HTML is `<h3>`, in Markdown is `###`), and subsections are using level 4 (in HTML is `<h4>`, in Markdown is `####`).

The idea is to have
+ `2` empty lines between last suggested book & new header.
+ `1` empty line between header & first book of that very section.
+ `0` empty line between each book in 1 section.
+ `1` empty line at the end of each `.md` file.

Example:

    [...]
    * [An Awesome Book](http://example.com/example.html)
                                    (blank line)
                                    (blank line)
    ### Example
                                    (blank line)
    * [Another Awesome Book](http://example.com/book.html)
    * [Some Other Book](http://example.com/other.html)

- Don't put spaces between `]` and `(`

```
BAD : * [Another Awesome Book] (http://example.com/book.html)
GOOD: * [Another Awesome Book](http://example.com/book.html)
```

- If you include the author, use ` - ` (a dash surrounded by single spaces)

```
BAD : * [Another Awesome Book](http://example.com/book.html)- John Doe
GOOD: * [Another Awesome Book](http://example.com/book.html) - John Doe
```

- Put a single space between the link and its format

```
BAD : * [Another Awesome Book](http://example.com/book.pdf)(PDF)
GOOD: * [Another Awesome Book](http://example.com/book.pdf) (PDF)
```

- Author comes before format:

```
BAD : * [Another Awesome Book](http://example.com/book.pdf)- John Doe
GOOD: * [Another Awesome Book](http://example.com/book.pdf) - John Doe (PDF)
```

- Multiple formats:

```
BAD : * [Another Awesome Book](http://example.com/)- John Doe (HTML)
BAD : * [Another Awesome Book](https://downloads.example.org/book.html)- John Doe (download site)
GOOD: * [Another Awesome Book](http://example.com/) - John Doe (HTML) [(PDF, EPUB)](https://downloads.example.org/book.html)
```

- Include publication year in title for older books:

```
BAD: * [Another Awesome Book](http://example.com/book.html) - John Doe - 1970
GOOD: * [Another Awesome Book (1970)](http://example.com/book.html) - John Doe
```
We hope you contribute to this great repository. :+1:
