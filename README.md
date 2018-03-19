
## R Markdown to PowerPoint

You can create PowerPoint presentations from R Markdown files using RStudio. Warning: This feature is experimental; do not attempt current or production systems. The following instructions have been tested for Linux.

### Install

#### Pandoc

You will need to manually install and link to the latest version of Pandoc. Eventually Pandoc 2 will be bundled into the IDE, but for now, this remains a manual process. Warning: Changing the location of your Pandoc installation may break your code.

```
wget https://github.com/jgm/pandoc/releases/download/2.1.2/pandoc-2.1.2-linux.tar.gz
tar xzvf pandoc-2.1.2-linux.tar.gz
ln -s /opt/pandoc-2.1.2/bin/pandoc /usr/local/bin/pandoc
```

#### R packages

You should also upgrade the rmarkdown and knitr packages. You will want to install the webshot package so you can take screenshots of your Shiny apps and include them in your presentations.

```
install.packages('rmarkdown')
install.packages('knitr')
install.packages("webshot")
webshot::install_phantomjs()
```

#### RStudio 1.2

Version 1.2 of RStudio contains user features for creating PowerPoint presentations. Currently, RStudio 1.2 is also experimental. You can upgrade to the latest version of RStudio by downloading and installing the [daily builds](https://dailies.rstudio.com/).

### Demos

This package contains demos for creating PowerPoint presentations from R Markdown. All standard markdown format is supported in the PowerPoint output, as well as some nice features, including:

* Bullets and numbering
* Multiple columns
* Linked images
* Equations
* Code
* Text formatting
* Tables
* Templates

Note that if you want to change the slide dimensions or any other aesthetics, you should make those changes in the PowerPoint template.