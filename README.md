# UNHCR Quarto HTML document template

A [Quarto](https://quarto.org/) extension to create [UNHCR branded](https://www.unhcr.org/brand) `HTML` document.

## Installing

Tu use the template, you need first to install the most recent version of [quarto (at last version 1)](https://quarto.org/docs/get-started/) - Note that if you are on Ubuntu, the default version on repo might not be the most recent one.

To start a new `HTML` document, before creating your project on Rstudio, run in a regular terminal (not an R command):

```bash
quarto use template unhcr-dataviz/quarto-html-unhcr
```

This will install UNHCR extension and create an example `.qmd` file that you can use as a starting place for your article.

On your screen you will see

```
Quarto templates may execute code when documents are rendered. If you do not 
trust the authors of the template, we recommend that you do not install or 
use the template.
 ? Do you trust the authors of this template (Y/n) › Yes
 ? Directory name: › 
```

For `Directory name`, enter the name of an empty folder. Once this is done, you can create a project from Rstudio, using `Existing Directory`.

Once in RStudio, you can simply Render the file to create your html report. Quarto also offers the possibility to see on constant basis the equivalent visual of your report (switch between Source and visual on the top left part of your report panel.

## Documentation

Read the [Quarto documentation on HTML documents](https://quarto.org/docs/output-formats/html-basics.html)

## Example

Here is the [source code](template.qmd) and the [live example](https://unhcr-dataviz.github.io/quarto-html-unhcr/) of the [template.qmd](template.qmd) file.
