---
title: "Interpreting results"
teaching: 10
exercises: 2
---

:::::::::::::::::::::::::::::::::::::: questions 

- How do I know that this is the most appropriate method to use for prioritisation?
- How can I know that i'm interpreting user feedback correctly? 
- How can i know that the grouping and labelling is the correct way to group and label?
- Know i have feedback that i can apply to my highest priorities, how can I define an action or a change informed by this feedback?

::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: objectives

- To make a choice of a 'high-priority' measurement, based on application of a method, having read and reviewed those methods, to the demo project.
- Making better, more informed decisions about design.
- Demonstrate how to group and label user feedback and assertain which are applicable to your high priorities or not and why.

::::::::::::::::::::::::::::::::::::::::::::::::

## Introduction

This is a lesson created via The Carpentries Workbench. It is written in
[Pandoc-flavored Markdown](https://pandoc.org/MANUAL.html) for static files and
[R Markdown][r-markdown] for dynamic files that can render code into output. 
Please refer to the [Introduction to The Carpentries 
Workbench](https://carpentries.github.io/sandpaper-docs/) for full documentation.

What you need to know is that there are three sections required for a valid
Carpentries lesson:

 1. `questions` are displayed at the beginning of the episode to prime the
    learner for the content.
 2. `objectives` are the learning objectives for an episode displayed with
    the questions.
 3. `keypoints` are displayed at the end of the episode to reinforce the
    objectives.

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::: instructor

Inline instructor notes can help inform instructors of timing challenges
associated with the lessons. They appear in the "Instructor View"

::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::: challenge 

## Challenge 1: Can you do it?

What is the output of this command?

```r
paste("This", "new", "lesson", "looks", "good")
```

:::::::::::::::::::::::: challenge

Firstly what is your highest priority for software right now? What has informed that high priority?

Write down a list (no more than 6) of what you consider your highest priorities right now for your software.

::::::::::::::::::::::::  



:::::::::::::::::::::::: solution 

## Output
 
```output
[1] "This new lesson looks good"
```

:::::::::::::::::::::::::::::::::


::: tab

### Windows

Some Windows instructions

::::::::::::::::::::::::::::::::::::: challenge

Q: If you aren't part of the solution, then what are you?

:::::::::::::::: solution

A: part of the precipitate

:::::::::::::::::::::::::
:::::::::::::::::::::::::::::::::::::::::::::::

### Mac

Maybe some for Mac

::::::::::::::::::::::::::::::::::::: challenge


Q: If you aren't part of the solution, then what are you?

:::::::::::::::: solution

A: part of the precipitate

:::::::::::::::::::::::::
:::::::::::::::::::::::::::::::::::::::::::::::

### Linux

And more for Linux users, including a code block:

::::::::::::::::::::::::::::::::::::: challenge


Q: If you aren't part of the solution, then what are you?

:::::::::::::::: solution

A: part of the precipitate

:::::::::::::::::::::::::
:::::::::::::::::::::::::::::::::::::::::::::::

```python
  print("Yay, tabs!")
```

:::




## Challenge 2: how do you nest solutions within challenge blocks?

:::::::::::::::::::::::: solution 

You can add a line with at least three colons and a `solution` tag.

:::::::::::::::::::::::::::::::::
::::::::::::::::::::::::::::::::::::::::::::::::

## Figures

You can use standard markdown for static figures with the following syntax:

`![optional caption that appears below the figure](figure url){alt='alt text for
accessibility purposes'}`

![You belong in The Carpentries!](https://raw.githubusercontent.com/carpentries/logo/master/Badge_Carpentries.svg){alt='Blue Carpentries hex person logo with no text.'}

::::::::::::::::::::::::::::::::::::: callout

Callout sections can highlight information.

They are sometimes used to emphasise particularly important points
but are also used in some lessons to present "asides": 
content that is not central to the narrative of the lesson,
e.g. by providing the answer to a commonly-asked question.

::::::::::::::::::::::::::::::::::::::::::::::::


## Math

One of our episodes contains $\LaTeX$ equations when describing how to create
dynamic reports with {knitr}, so we now use mathjax to describe this:

`$\alpha = \dfrac{1}{(1 - \beta)^2}$` becomes: $\alpha = \dfrac{1}{(1 - \beta)^2}$

Cool, right?

::::::::::::::::::::::::::::::::::::: keypoints 

- Use `.md` files for episodes when you want static content
- Use `.Rmd` files for episodes when you need to generate output
- Run `sandpaper::check_lesson()` to identify any issues with your lesson
- Run `sandpaper::build_lesson()` to preview your lesson locally

::::::::::::::::::::::::::::::::::::::::::::::::

[r-markdown]: https://rmarkdown.rstudio.com/
