---
title: Demo book
author: Desiree De Leon
date: 08/09/2019
site: bookdown::bookdown_site
documentclass: book
bibliography:
- book.bib
- packages.bib
link-citations: true
biblio-style: apalike
description: A work in progress.
favicon: images/favicon.ico
cover-image: images/logo-black.png
github-repo: dcossyleon/fake_book
---

# Prerequisites {-}

This is a _sample_ book written in **Markdown**. You can use anything that Pandoc's Markdown supports, e.g., a math equation $a^2 + b^2 = c^2$.

The **bookdown** package can be installed from CRAN or Github:


```r
install.packages("bookdown")
# or the development version
# devtools::install_github("rstudio/bookdown")
```

Remember each Rmd file contains one and only one chapter, and a chapter is defined by the first-level heading `#`.

To compile this example to PDF, you need XeLaTeX. You are recommended to install TinyTeX (which includes XeLaTeX): <https://yihui.name/tinytex/>.




:::demo
This signals a placeholder for when live-coding or another demo is occurring.
:::

:::puzzle
This signals an activity or challenge for you to try
:::

:::note
This points out a tip that may be useful for a workflow or process
:::

:::fyi
This proves more background in case you're interesting in knowing more
:::

