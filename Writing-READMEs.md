



> Written with [StackEdit](https://stackedit.io/).

##### LESSON 1

#### Writing READMEs

Learn the importance of well documented code and see how to craft meaningful READMEs.

## Who is Documentation For?

When you hear the phrase technical documentation you might think of dry literature that is difficult to understand. But good documentation isn't boring or unapproachable -- often it's written in plain English! Sometimes, it's even written as a series of guides or tutorials.

As it turns out, there isn't a secret ruling body that makes laws for what documentation should and shouldn't look like. That's because unlike your code which is written for computers documentation is written for humans. Documentation exists to help us make sense of the code that we've written, which may not always be quite as intuitive as we'd like it to be.

For instance if you're working a large open source library that other people can use, good documentation is absolutely essential for acquiring both users and contributors. If your documentation is good, people will want to use your library in their projects. If your documentation is  _great_, people might even chip in and help you with your library.

Perhaps your project is a portfolio piece to help you land your first job. As a developer, in that case you'll want to document your work in a way an employer can easily skim and pull relevant information. Give some thought as to who is going to be reading your documentation. You'll want it to be easy for anyone to dive into your code and get it up and running without any hiccups!

## Anatomy of a README

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

-

Press your project has received doesn't really help us actually use your code, so it's not a good fit for a README (this might be something more appropriate for your own website). Photos of your cat might fare better elsewhere as well, rather than your README.

# Markdown 101

Markdown is a light markup language often used for READMEs (though you'll find other use cases for it, too!). It is fairly straightforward, and much of the syntax is intuitive.

But as it turns out, there are many different  _dialects_  of Markdown, just like in a spoken language. Each of these dialects is known as a  _flavor_  of Markdown. Most of these dialects are pretty much the same, with only minor differences.

Since your READMEs will ultimately end up on GitHub, we'll be using  **GitHub Flavored Markdown**. I've included a link to the full documentation for it in the instructor notes (and we'll be using that later in this course), but I'll get you started with a quick crash course.

## Feeling Bold?

To make text  **bold**, surround it with double asterisks. So this code:

```
Isn't today a **wonderful** day?

```

becomes: Isn't today a  **wonderful**  day?

This reads a bit more nicely than a  `<strong>`  tag would in HTML, and takes considerably fewer keystrokes to type out.

## _Italics_, I tell you!

To  _italicize_  text, surround it with underscores. So this code:

```
And in that moment I thought to myself: _Did I turn off the stove?_

```

becomes: And in that moment I thought to myself:  _Did I turn off the stove?_

Much like the previous example, this code reads much more like English, which is great for when you're skimming the original document.

## To  `code`, or not to  `code`?

Inline  `code`  is useful for indicating that you're writing code and not a regular word. For this, you'll surround text in backticks (`, not a single quote). So this code:

```
You should use the `strong` tag.

```

becomes: You should use the  `strong`  tag.

...which makes much more sense than "You should use the strong tag."

## The Title Sequence

Headings are even simpler! For  `h1`  through  `h6`  tags, all you'll need is a  `#`  before your text. The number of  `#`s you include tells Markdown which header tag you're using. For example:

`## This is an h2.`

`### This is an h3.`

becomes...

## This is an h2.

### This is an h3.

Let's practice!

Here's a link to the basic  [Markdown documentation](https://help.github.com/articles/markdown-basics/). You can also check out the differences in GitHub flavored Markdown  [here](https://help.github.com/articles/github-flavored-markdown/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQ3MDYzNzQyLDEwMDEwMDA5NzksMTY5MT
Y4ODc0NiwtMTI5MjM3NTM5Nyw1Mjg1NDQ2NzgsMTA0NjU0ODMw
NF19
-->