# CSU Applied Category Theory Seminar Website

https://csu-applied-category-theory.github.io/

## How do I get edit access?

Create a GitHub account, and ask a seminar organizer to add that account to the GitHub organization.

## What is the format of this repository?

Markdown files are what will be displayed on the website. The top nav is sorted by file prefix. (i.e `00-xxx.md` before `01-yyy.md`). In each the preemble 
```
---
title: MY_TITLE
nav: true
---
``` 
gives the title of the page and shows it in the nav.

## How do I make changes?

Make changes either directly with the Web UI on the [repository](https://github.com/csu-applied-category-theory/csu-applied-category-theory) page, or locally with an editor after pulling. Push directly to the main branch and changes to the website will be reflected in a minute. (Look for the green checkmark to the left of your commit)

Everything is in [markdown](https://kramdown.gettalong.org/quickref.html), LaTeX formatting is supported with MathJax, including using single dollar signs (`$...$`) as delimiters.

### How do I add images?

Check in an image under the `images` directory, and use the Markdown snippet `![image](./images/uidaho-workshop.jpg)`

### Can I see my changes locally?

If you install Ruby, Bundle, and Jekyll, and install the gems with `bundle install`, then `jekyll serve` will allow you to make changes and see the website update. 

Please talk to Chris if you run into trouble with installation issues above.
