# Sample Input and Output

These files describe input R Markdown documents and an example PowerPoint output. 

## Input 

The input R Markdown include two file formats:

* [iolides](ioslides_input_with_shiny.Rmd) which renders [here](http://colorado.rstudio.com:3939/content/314/). This includes a Shiny app on the last slide.
* [notebook](document_input.Rmd) which renders [here](http://colorado.rstudio.com:3939/content/313/sampleInput.nb.html). This does not include a Shiny app.

## Output

The output file is a PowerPoint presentation called `powerpoint_output.pptx`. The PowerPoint presentation contains the following features:

* Source code. Click this button to download source code. Used for reproducibility and makes it similar to R Markdown notebooks. This feature is optional (Is it even possible?)
* Text rendered in markdown. This includes hyperlinks, bullets, tables, and other standard markdown formatting. This is a required feature.
* Code and code output. This includes all R code and output from the console. This is an optional feature.
* Various plots with hyperlinks. This would include base graphics, ggplot2, and all other static graphics. This is a required feature. The images can also be linked to a hosted version online. This allows user to save low resolution images to PowerPoint while preserving high resolutions online. This second feature is optional.
* HTML Widgets with hyperlinks. Screenshots of the htmlwidgets with hyperlinks back to the hosted images allow developers to point their audience to interactive visualizations. This feature is optional.
* Shiny web apps with hyperlinks. Like HTML widgets, these apps would be hosted online but would be rendered as static images with a hyperlink. This feature is also optional.



