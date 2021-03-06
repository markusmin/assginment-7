# assginment-7

## Package title
ggpubr

## Location
This package is on CRAN [here](https://cran.r-project.org/web/packages/ggpubr/index.html) and on GitHub [here](https://github.com/kassambara/ggpubr).

## Vignette(s)
A vignette of the package written by the package author can be found [here](https://rpkgs.datanovia.com/ggpubr/). This vignette goes over some of the many plotting functions in this package, such as ggbarplot(), ggboxplot(), and ggdensity(), which are more intuitive, aesthetically pleasing, and simple than the base ggplot2 functions for making these plots. 

## Application(s)
[This article on medium](https://medium.com/swlh/beautiful-charts-with-r-and-ggpubr-c94122d6b7c6) goes over some examples of how this package can be used to plot data. However, I don't find it to be much more useful than the documentation/vignette written by the author.

## Review
ggpubr is an extension of ggplot2, with many new functions that make plotting data more intuitive and user-friendly. However, for the experienced R/tidyverse user, these new plotting functions may not be super useful. This package was fairly easy to use, and I would certainly recommend it to others!

Where this package excels (from my perspective as someone who is comfortable with ggplot2) is with the **ggarrange()** function used to arrange plots, which is extremely helpful for making publication-ready multipanel figures. I used to use Powerpoint or Illustrator to arrange plots that I saved using ggsave(), but the ggarrange() function makes this much easier and allows your final figures to be more reproducible and neat. You can annotate multipanel figures easily with letters, change the heights/widths of figures, and align figures easily. If ggpubr::ggarrange() isn't cutting it for you, there's also the egg::ggarrange() function (vignette found [here](https://cran.r-project.org/web/packages/egg/vignettes/Overview.html)), which gives more options for arranging figures, many of which are complementary to functionality of the ggpubr::ggarrange() function. 

