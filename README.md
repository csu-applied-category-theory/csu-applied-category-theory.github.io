# CSU Applied Category Theory Seminar Website

https://csu-applied-category-theory.github.io/

## How can I get edit access?

Create a GitHub account, and ask a seminar organizer to add that account to the GitHub organization.

## What is the format of this repository?

Content is in [markdown](https://kramdown.gettalong.org/quickref.html), LaTeX formatting is supported with MathJax, including using single dollar signs (`$...$`) as delimiters.

The top nav is sorted by file prefix. (i.e `00-xxx.md` before `01-yyy.md`). In each the preemble 
```
---
title: MY_TITLE
nav: true
---
``` 
gives the title of the page and shows it in the nav.

## How can I make changes?

Make changes either directly with the Web UI on the [repository](https://github.com/csu-applied-category-theory/csu-applied-category-theory) page, or locally with an editor after pulling. Push directly to the main branch and changes to the website will be reflected in a minute.

 Look for the green checkmark to the left of your commit, if you see a red `X`, an error has occured. You may need to clear your cache to see the changes reflected. (cmd-shift-R on OSX, ctrl-F5 on window/Linux)


### How can I add an image?

Check in an image under the `images` directory, and use the Markdown snippet `![image](./images/MY_IMAGE_NAME.jpg)`

### How can I see my changes locally?

If you install Ruby, Bundle, and Jekyll, and install the gems with `bundle install`, then `jekyll serve` will allow you to make changes and see the website update. 

Please talk to Chris if you run into trouble with installation issues above.
