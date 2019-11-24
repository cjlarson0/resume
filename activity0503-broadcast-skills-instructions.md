---
title: "Activity 5.3"
output: 
  html_document: 
    keep_md: yes
---



# Broadcasting your skills: Résumés and Personal Websites

Requirements:

- GitHub account
- RStudio Cloud account

Goals:

- Create a document to share with your skills with future employers.

## Introduction

There are a number of packages that can aid in producing a résumé or personal website in R/RStudio.
For résumés, I prefer the [`vitae`](https://github.com/mitchelloharawild/vitae) package as it has a number of built in templates and is fairly straightforward to [create your own template](https://pkg.mitchelloharawild.com/vitae/articles/extending.html).
For building a personal website, there is no competition - use [`blogdown`](https://github.com/rstudio/blogdown).

## Getting started

This is an individually submitted activity, but I highly encourage you all to help your Team Members out.
Creating a résumé or personal website with R is relatively painless and focuses more on your markdown skills than anything else, really.

### Résumés

In addition to the `vitae` package, the [`pagedown`](https://github.com/rstudio/pagedown) package is another option, that can also handle posters, articles, business cards, and more!
The [Other examples](https://github.com/rstudio/pagedown#other-examples) section provides some links to users that have created different documents using `pagedown`.

The author of vitae also provided a brief tutorial here: https://ropensci.org/blog/2019/01/10/vitae/.
Also, check out the [Examples of using vitae](https://github.com/mitchelloharawild/vitae#examples-of-using-vitae) linked on the `vitae` repo.

### Personal website

Pick a [Hugo theme](https://themes.gohugo.io/).
Once you decide on a theme you like, you will need to have the GitHub username and repo for that theme.
After you get things set-up, its just adding content (pages or posts).

[Yihui](https://yihui.org/), [Amber](https://amber.rbind.io/), and [Alison](https://alison.rbind.io/) have provided a free book to help with creating a website: [blogdown: Creating Websites with R Markdown](https://bookdown.org/yihui/blogdown/).
This goes into great detail of the process, but there are a number of great tutorials that simplify this process:

- To create a GitHub page (e.g., "yourusername.github.io"), see this post by Nikhil Kaza: https://sia.planning.unc.edu/post/using-blogdown/
- To create a Netlify page, see Martin Frigaard's post: http://www.storybench.org/how-to-build-a-website-with-blogdown-in-r/

### Other posibilities

If you ever decide to make a poster for conference presentation (or just for fun?), there's a package for that: [`posterdown`](https://github.com/brentthorne/posterdown).
I love the `poster_betterland` template.
Mike Morrison provides a good explination behind this poster design (19 min 31 sec): [#betterposter](https://www.youtube.com/watch?v=1RwJbhkCA58).

When you have completed your résumé or personal website, post a *clickable* link to your website or the repo containing your résumé and a reflection on this task at the **Application 7** on Bb.
This is due Sunday, Dec. 1st by 11:59 pm.

