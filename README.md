# SSC_Markdown_Workshop
Playing around with markdown, LaTeX, making pretty reports
April 22, 2016

---
## Why not use Word or Google Docs?
---
## Why not use Word or Google Docs?
* Easier - Never take your fingers off the keyboard
* Focus on content, not layout
* Better integration with code or charts
* Push it to and edit on GitHub
* Free, open-source, anyone can use and edit without proprietary software
* Easily export to pdf, html, etc.
---

![pictcha](http://media.tumblr.com/a009269b9f0aa039c03a723f4d71b9f0/tumblr_inline_mmwltulZIC1qz4rgp.png)
---
## What's a markup language?

--
**From Wikipedia**:
> A markup language is a system for annotating a document in a way that is syntactically distinguishable from the text.[1] The idea and terminology evolved from the "marking up" of paper manuscripts, i.e., the revision instructions by editors, traditionally written with a blue pencil on authors' manuscripts.

Like HTML (Hyper Text Markup Language)!
---

## Markdown vs LaTeX

|Markdown | LaTeX|
|----|---|
|Lightweight | Power|
|John Gruber | Donald Knuth |
|Supports HTML tags| Based on TeX |
|Math not really supported| All the Greek all the Time |

---
## Markdown In Action

### The Basics
```
The *quick* brown fox, jumped **over** the lazy [dog](https://en.wikipedia.org/wiki/Dog).  
```
The *quick* brown fox, jumped **over** the lazy [dog](https://en.wikipedia.org/wiki/Dog).

### Headings
```
# H1
## H2
### H3
```
# H1
## H2
### H3

---
### Tables
```
|Pipes | Make | It| Easy|
|--|--|--|
|See | how| easy| it is?|
```
|Pipes | Make | It| Easy|
|---|---|---|
|See | how| easy| it is?|
---
## Quotes

> If you can't make it good, at least make it look good. - Bill Gates

---
## Displaying Code
```
You can do in-line stuff `like this` or you can do blocks like this:
```
You can do in-line stuff `like this` or you can do blocks like this:
```
def make_report(adjective):
    if adjective == 'ugly':
         print('Use word!')
    if adjective == 'pretty':
         print('Use Markdown, silly!)
         
make_report(pretty)
'Use Markdown, silly!
```
---
## Fancier Stuff
 ```
 ~~strikethrough~~
 
 * List
 * More List
 * This List is Forever
 
 1. Numbers
 3. Are
 5. All
 6. Screwed
 8. Up
 44. But it still works!
 
 ```
  ~~strikethrough~~
 
 * List
 * More List
 * This List is Forever
 
 1. Numbers
 3. Are
 5. All
 6. Screwed
 8. Up
 44. But it still works!
 
 Github also supports emojis like :umbrella: :purple_heart:
---
## Pictures!

![atom](https://i.github-camo.com/c78b3c01ca7753c84d26706b248adf236cda7d4f/68747470733a2f2f636c6f75642e67697468756275736572636f6e74656e742e636f6d2f6173736574732f3337383032332f31303031333038372f32346363633765632d363134392d313165352d393765612d3533613834326137313565612e706e67)

---
## All of the tools!
### Report Generation
* [Madoko](https://www.madoko.net)
* [R Markdown](http://rmarkdown.rstudio.com/)
* [Overleaf](https://www.overleaf.com/) for LaTeX. Allows doc sharing, requires sign up.
* [ShareLaTeX](https://www.sharelatex.com/) for LaTeX. Also requires sign up.

### Presentations:

No Sign Up:
* [Madoko](https://www.madoko.net) again
* [Remarkise](https://gnab.github.io/remark/remarkise)

Requires Sign Up:
* https://www.swipe.to

---
## Still more tools!
### Web and General Text Editing
* http://dillinger.io/
* https://stackedit.io/editor

**Don't forget!** You can always use your favorite text editor! I use [Atom](https://atom.io/), but [Sublime Text](sublime text) supports Markdown too. Emacs has out of the box LaTeX integration.

There are lots of paid ones too, but why use those when you can use **free** and **open-source**?
---
## Now let's make something!

Try using your own editor, Makodo, Swipe, or R Markdown to generate a report or deck. We'll share at the end! 

Come up with your own idea, or check out these iPython Notebooks for inspiration and example code/text to report on or present:

* [Gallery of Interesting iPython Notebooks](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks)
* [Starry Night Notebook](http://nbviewer.jupyter.org/github/jiffyclub/ipythonblocks/blob/master/demos/starry_night_to_text.ipynb)
* [XKCD Matplotlib Library](http://nbviewer.jupyter.org/url/jakevdp.github.com/downloads/notebooks/XKCD_plots.ipynb)

Don't forget to use:
* Headings, Tables, Code Insert, Quotes

If you feel like it, try inserting:

* An Equation, A Picture, Footnotes, HTML Snippets, Horizontal Rules

Or if you are super into it:

* Create your own HTML template or find another one to integrate with it

---
## Further Reading
* More [Markdown Tools](https://github.com/adam-p/markdown-here/wiki/Other-Markdown-Tools)
* Ghost's [Complete Guide to Markdown](https://blog.ghost.org/markdown/)
* [Markdown Tutorial](http://www.markdowntutorial.com/)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* R Markdown [Cheatsheet](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf) and 
* [The (Not So) Short Introduction to LaTeX2e](http://mirrors.rit.edu/CTAN/info/lshort/english/lshort.pdf)
* [Comprehensive LaTeX Symbol List](http://bay.uchicago.edu/tex-archive/info/symbols/comprehensive/symbols-letter.pdf)
* I stole info from [Markdown, Latex, Etc.](https://gist.github.com/zmwangx/9987772)
* Good [example](http://kieranhealy.org/files/misc/article-markdown.pdf) of using pandoc in a reporting workflow by Kieran Healy with a [howto](https://kieranhealy.org/blog/archives/2014/01/23/plain-text/)
* [Datacamp R Markdown] Tutorial (https://www.datacamp.com/community/blog/r-markdown-tutorial-reproducible-reporting-in-r)
