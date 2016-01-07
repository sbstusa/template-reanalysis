
This repository contains templates that can be used to write reports or presentations for SBST related work.

# Setup

Right now, the resources here use [R Markdown](http://rmarkdown.rstudio.com/) for authoring of reports and presentations. To use them, you'll need to install some of the SBST Design Elements

## Install the SBST Design Elements

### The SBST Fonts

The SBST font is Lato. The workflow here assumes that you've installed the [Lato Font](http://www.latofonts.com/) to your system. 

### SBST Logos

These ought to be part of the repository even though they are binary files, they do not change. 

### SBST Colors

The colors are defined in the templates which allow [pandoc](http://pandoc.org/) to convert

## Install R Packages

I think that if you are editing files using RStudio, then you can just click "Knit to PDF" or "Knit to HTML". If you are using R some other way, then you'll need to have installed rmarkdown (`install.packages('rmarkdown')`). You can create pdf or html output using the `render()` function. For example, `render('myfile.Rmd')`.

# Help

We can use the [Github Wiki](https://github.com/sbstusa/templates/wiki) to collaboratively write up little tutorials. We can use [Github Issues](https://github.com/sbstusa/templates/issues) to organize work and record bugs and problems.


