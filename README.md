# Typst-factsheet Format

## Installing

_TODO_: Replace the `<github-organization>` with your GitHub organization.

```bash
quarto use template <github-organization>/typst-factsheet
```

This will install the format extension and create an example qmd file
that you can use as a starting place for your document.

## Using

_TODO_: Describe how to use your format.



# typst-factsheet

This workspace is a private trial to test the creation of a typst template for quarto ... and learn about how things work together.


## Overview 

Some breadcrumbs for latter documentation

* Quarto - scientific publication
* typst - 'new' typesetting for document publishing and layout framework particularly pdf
'better' / less resource-intensive than LATEX
other benefits - easier to learn

Short familiarisation - follow tutorial or click through it on typst online app.

## Creating a Quarto Typst template
Quarto calls (typst) templates `custom format extensions`.    
The principal approach is explained in https://quarto.org/docs/extensions/formats.html.

In the terminal type:
    `quarto create extension format:typst`

When queried insert extension name, e.g. typst-factsheet

Creating extension at /Users/rainerkoelle/RProjects/typst-factsheet/typst-factsheet:
    - Created README.md
- Created template.qmd
- Created _extensions/typst-factsheet/typst-template.typ
- Created _extensions/typst-factsheet/typst-show.typ
- Created _extensions/typst-factsheet/_extension.yml