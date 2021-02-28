# Assignment 2: Data wrangling 

This repository contains starter code for your second assignment, which is all about practicing your data wrangling skills. You are free to use whatever methods and packages you prefer (e.g. tidyverse and/or data.table). I only expect you to document and comment your code clearly.

The goal of the assignment is to analyse EIA (Energy Information Agency) data on US coal exports from 2002 until the present. The structure of the newly-cloned repository is as follows:

```
repo
|
-- README.md
|
-- .gitignore
|
-- data
|  |
|  -- (empty)
|
-- R
   |
   -- coal.Rmd

```

You should clone this repo using the RStudio Project method that we practiced in class. Then, I want you to open up the `R/coal.Rmd` file where you will find the questions and basic template for providing your answers. You should answer each question by inserting R code chunks (like we practiced in class) in the relevant spaces. Whenever you "knit" this `R/coal.Rmd` file, you will produce the corresponding `R/coal.md` (i.e. Markdown) and `R/coal.html` (i.e. HTML) files, as well as some auxiliary folders. Don't worry about those now; they are just to help speed things up and my template should take care of everything for you.

Last things: Please pay attention when I ask you to comment on your results in addition to coding them up. **And please mark your comment answers in bold so that I can easily identify them.**

## Grade A

I was erring towards an "A-" because of some of the issues below. But you managed to pull yourself back up the extra half an inch thanks to generally excellent/humorous discussion and comments. Good job on the internet sleuthing.

- Q 3. Not quite what I was looking for, but the main gripe I have with the plot is duplicating information across aesthetics (i.e. y axis and point size both convey "total"). This can work well in some cases like density fills (e.g. [here](https://wilkelab.org/ggridges/articles/gallery.html#temperatures-in-lincoln-nebraska-1)), but generally you want to avoid it. Each aesthetic should map onto a unique aspect of the data.
- Q 4.2 dplyr exports the same `count()` function.
- Q 4.5/6 I asked for a vector not a tibble.
- Q 4.7 I asked for _quarterly_ exports.
- Q 4.8 Nice but see my explicit discussion of stacked area plots in the solution key.
