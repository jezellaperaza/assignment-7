# assignment-7
A repo for assignment 7.

## Package title
*What is the package’s title?*

The title of this package is dadjokeapi. 

## Location
*From where can you install this package on the web? Is it on CRAN or GitHub or both?*

You can access this package from GitHub by installing as so: 
``` r
# install.packages("devtools")
devtools::install_github("jhollist/dadjokeapi")
```

And it is also on CRAN as so:
```r
install.packages("dadjokeapi")
```

## Vignette(s)
*Does the package have any formal vignettes, or just the standard collection of help files? If there are one or more vignettes, what topics do they cover?*

This package unfortunately has no vignettes. Which is extremely disappointing, I think this needs to change. But, there is a standard help file when you run:
```r
?groan
```

## Application(s)
*Are there any applications of the package, as demonstrated on a website like we built, someone’s blog, Twitter post, etc? If so, describe some of them.*

There is one application of this package, and it's this incredible website: https://icanhazdadjoke.com/. The package is used in this website to generate a new dad joke every time you click the green button "new joke" at the top of the webpage. 

A basic application of the package can be done as so:
```{r echo = TRUE}
dadjokeapi::groan()
```

Here is the generated joke:

**Today, my son asked "Can I have a book mark?" and I burst into tears. 11 years old and he still doesn't know my name is Brian.**

## Review
*Write a short (<300 words) review of the package. What is the primary purpose of the package (eg, is used for plotting, reading or scraping data, manipulating data, statistical modeling, etc)? What are the things you like about the package? Are there things you don’t like or wish it did differently? Was the package easy to learn how to use? Would you recommend this package to someone else?*

The primary purpose of this package, as defined by the creator themselves, is to "make you laugh in spite of yourself." Whenever you are feeling down, just generate a new dad joke for giggles. What I really like about this package is its simplicity in that it is a single function. A plus is the function being named "groan," it can't get better than that. I do wish this package had more functions. For example, maybe different functions to generate different dad jokes that fall under certain categories like "one-liners," "corny," "cringeworthy," and "pun-tastic." I think there's real potential here. I 100% recommend this package for anyone who needs a dad joke on the fly!
