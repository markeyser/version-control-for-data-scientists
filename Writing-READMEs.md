



> Written with [StackEdit](https://stackedit.io/).

##### LESSON 1

#### Writing READMEs

Learn the importance of well documented code and see how to craft meaningful READMEs.

1. [Welcome](https://github.com/markeyser/version-control-for-data-scientists/blob/master/Writing-READMEs.md#1-welcome)
2. [What is Documentation?](https://github.com/markeyser/version-control-for-data-scientists/blob/master/Writing-READMEs.md#2-what-is-documentation)
3. [Who is Documentation For?](https://classroom.udacity.com/courses/ud777/lessons/5338568539/concepts/c9d82ab5-d56f-455c-9a34-b64eecc4c9c5 "3. Who is Documentation For?")
4. [How Does Nija Consume Documentation?](https://classroom.udacity.com/courses/ud777/lessons/5338568539/concepts/54131785380923 "4. How Does Nija Consume Documentation?")
5. [Why Should Art Have Documented His Code?](https://classroom.udacity.com/courses/ud777/lessons/5338568539/concepts/53928293410923 "5. Why Should Art Have Documented His Code?")
6. [Introduction to READMEs](https://classroom.udacity.com/courses/ud777/lessons/5338568539/concepts/876fb9ad-54c9-457f-b41b-b2676a30806b "6. Introduction to READMEs")
7. [Anatomy of a README](https://classroom.udacity.com/courses/ud777/lessons/5338568539/concepts/53317786160923 "7. Anatomy of a README")
8. [Documenting a Growing Codebase](https://classroom.udacity.com/courses/ud777/lessons/5338568539/concepts/e79fba65-50e5-44b9-a29f-850a8b6600a2 "8. Documenting a Growing Codebase")
9. [Readable READMEs with Markdown](https://classroom.udacity.com/courses/ud777/lessons/5338568539/concepts/53317786210923 "9. Readable READMEs with Markdown")
10. [Basic Markdown Syntax](https://classroom.udacity.com/courses/ud777/lessons/5338568539/concepts/53931993710923 "10. Basic Markdown Syntax")
11. [Basic Markdown Syntax Quiz](https://classroom.udacity.com/courses/ud777/lessons/5338568539/concepts/456a380f-64c8-4b33-913e-dc2ad90efbf8 "11. Basic Markdown Syntax Quiz")
12. [More Markdown Syntax](https://classroom.udacity.com/courses/ud777/lessons/5338568539/concepts/53861592300923 "12. More Markdown Syntax")
13. [Quiz: Markdown Syntax Practice](https://classroom.udacity.com/courses/ud777/lessons/5338568539/concepts/53853602320923 "13. Quiz: Markdown Syntax Practice")
14. [Document Everything!](https://classroom.udacity.com/courses/ud777/lessons/5338568539/concepts/53929794080923 "14. Document Everything!")


## 1. Welcome

https://youtu.be/zYyRDFx3e28

## 2. What is Documentation?

https://youtu.be/IgOMI4_wQ54

## 3. Who is Documentation For?

When you hear the phrase technical documentation you might think of dry literature that is difficult to understand. But good documentation isn't boring or unapproachable -- often it's written in plain English! Sometimes, it's even written as a series of guides or tutorials.

As it turns out, there isn't a secret ruling body that makes laws for what documentation should and shouldn't look like. That's because unlike your code which is written for computers documentation is written for humans. Documentation exists to help us make sense of the code that we've written, which may not always be quite as intuitive as we'd like it to be.

For instance if you're working a large open source library that other people can use, good documentation is absolutely essential for acquiring both users and contributors. If your documentation is good, people will want to use your library in their projects. If your documentation is  _great_, people might even chip in and help you with your library.

Perhaps your project is a portfolio piece to help you land your first job. As a developer, in that case you'll want to document your work in a way an employer can easily skim and pull relevant information. Give some thought as to who is going to be reading your documentation. You'll want it to be easy for anyone to dive into your code and get it up and running without any hiccups!

## 4. How Does Nija Consume Documentation?

https://youtu.be/qkhZ9kTly9k

## 5. Why Should Art Have Documented His Code?

https://youtu.be/EBZxpavWMjk

## 6. Introduction to READMEs

### Anatomy of a README

Consider three README's for three different projects below:

1.  [factory_girl](https://github.com/thoughtbot/factory_girl)
2.  [can.viewify](https://github.com/zkat/can.viewify)
3.  [create-your-own-adventure](https://github.com/udacity/create-your-own-adventure)

As you examine each of the README's, take note of the following:

-   What information is being communicated?
-   How is this information structured?
-   Do you notice any patterns?

After you've taken a few moments to review the README's yourself, feel free to check the observations we made:

https://youtu.be/7ZHhSSBUzoI

As noted in the video above, feel free to use [Choose a License](http://choosealicense.com/) to help you, well... choose a license for your projects.

### QUIZ QUESTION

As a code base grows, which sections might you add to your README?

Press your project has received doesn't really help us actually use your code, so it's not a good fit for a README (this might be something more appropriate for your own website). Photos of your cat might fare better elsewhere as well, rather than your README.

## 7. Anatomy of a README

https://youtu.be/i602s2RxWR0

## 8. Documenting a Growing Codebase

### Documenting a Growing Codebase

https://youtu.be/4sU1LZksOH4

As noted in the video above, feel free to use  [Choose a License](http://choosealicense.com/)  to help you, well... choose a license for your projects.

## 9. Readable READMEs with Markdown

https://youtu.be/rWGxZGRwuAM

## 10. Basic Markdown Syntax

### Markdown 101

Markdown is a light markup language often used for READMEs (though you'll find other use cases for it, too!). It is fairly straightforward, and much of the syntax is intuitive.

But as it turns out, there are many different  _dialects_  of Markdown, just like in a spoken language. Each of these dialects is known as a  _flavor_  of Markdown. Most of these dialects are pretty much the same, with only minor differences.

Since your READMEs will ultimately end up on GitHub, we'll be using  **GitHub Flavored Markdown**. I've included a link to the full documentation for it in the instructor notes (and we'll be using that later in this course), but I'll get you started with a quick crash course.

### Feeling Bold?

To make text  **bold**, surround it with double asterisks. So this code:

```
Isn't today a **wonderful** day?

```

becomes: Isn't today a  **wonderful**  day?

This reads a bit more nicely than a  `<strong>`  tag would in HTML, and takes considerably fewer keystrokes to type out.

### _Italics_, I tell you!

To  _italicize_  text, surround it with underscores. So this code:

```
And in that moment I thought to myself: _Did I turn off the stove?_

```

becomes: And in that moment I thought to myself:  _Did I turn off the stove?_

Much like the previous example, this code reads much more like English, which is great for when you're skimming the original document.

### To  `code`, or not to  `code`?

Inline  `code`  is useful for indicating that you're writing code and not a regular word. For this, you'll surround text in backticks (`, not a single quote). So this code:

```
You should use the `strong` tag.

```

becomes: You should use the  `strong`  tag.

...which makes much more sense than "You should use the strong tag."

### The Title Sequence

Headings are even simpler! For  `h1`  through  `h6`  tags, all you'll need is a  `#`  before your text. The number of  `#`s you include tells Markdown which header tag you're using. For example:

`## This is an h2.`

`### This is an h3.`

becomes...

### This is an h2.

### This is an h3.

Let's practice!

Here's a link to the basic  [Markdown documentation](https://help.github.com/articles/markdown-basics/). You can also check out the differences in GitHub flavored Markdown  [here](https://help.github.com/articles/github-flavored-markdown/).

## 11. Basic Markdown Syntax Quiz

### Exercise: Basic Markdown Syntax

Let's do a quick review of some of the syntax you've learned. In the spaces provided, use the necessary mark-down to create each of words shown.

## 12. More Markdown

Now it's your turn. Dive into the  [Markdown documentation](https://help.github.com/articles/markdown-basics/), and explore more ways to write beautiful READMEs.

A few important items you may want to write and should pay extra attention to include:

-   Ordered and unordered lists
-   Links and images
-   Large blocks of code

### HTML Is Still a Thing

Something to keep in mind when using Markdown is that HTML is still valid in Markdown. If there's ever something fancy you can't accomplish with just Markdown, it's okay to fall back to HTML.

The catch here is that you may be overcomplicating your life. If you need to fall back to plain HTML, there's a good chance that you could communicate whatever it is you are trying to say in a simpler format.

### Working with  `.md`  Files

Much like how your HTML files should be saved with a  `.html`  extension, your Markdown files should be saved with a  `.md`  extension.

Markdown itself can't be opened in the browser like an HTML document. If you want to preview your Markdown files,  [Dillinger](http://dillinger.io/)  is a great online resource for you to do so.

If you are using Sublime Text, there is a  [plugin](https://packagecontrol.io/packages/GitHub%20Flavored%20Markdown%20Preview)  you can download to let you preview Markdown files right on your computer. If you are using Atom text editor, Markdown preview is baked right into the program (in the 'Packages' menu).

Here's a link to the basic  [Markdown documentation](https://help.github.com/articles/markdown-basics/). You can also check out the differences in GitHub flavored Markdown  [here](https://help.github.com/articles/github-flavored-markdown/).

To preview Markdown in the browser, try  [Dillinger](http://dillinger.io/).


## 13. Markdown Syntax Practice

https://youtu.be/sQj7ZSTk0U0

Here's a link to the basic [Markdown documentation](https://help.github.com/articles/markdown-basics/). You can also check out the differences in GitHub flavored Markdown [here](https://help.github.com/articles/github-flavored-markdown/).



## 14. Document Everything!

https://youtu.be/-rrim56YdmY
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTYwMzEzMDcyMSwtMjEwMjM3NzYxNSwxND
cwNjM3NDIsMTAwMTAwMDk3OSwxNjkxNjg4NzQ2LC0xMjkyMzc1
Mzk3LDUyODU0NDY3OCwxMDQ2NTQ4MzA0XX0=
-->