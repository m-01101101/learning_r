# Thinking as I go

I hope I look back on this note and realise how little I knew. This note is a forcing function for me to articulate what I do and don't know.

## Getting started

The first thing I'm struck by is the lack of a virtual environment. In Python, I'd set up a virutal environment. Is this not a thing in R? I've found `renv` but is this still installing to my base R installation?

> In short, you use renv::init() to initialize your project library, and use renv::snapshot() / renv::restore() to save and load the state of your library.

Downloading packages in R is slowwwww.

Running `library(somepackage)` is equivalent to ticking the box next to package in R studio

R markdown `Rmd` is akin to Jupyter, rendering the results of your code inline.

"Knitting" an R Markdown file means:

1. Execution: Running all R code chunks in the document.

2. Compilation: Converting the R Markdown (.Rmd) file into a final output format.

3. Integration: Combining narrative text, code, and results into a single document.

4. Output generation: Creating a formatted document (e.g., HTML, PDF, Word) that includes:
   - Text from the markdown
   - Executed R code
   - Results of the code (tables, plots, etc.)

The process allows for creating dynamic reports where code, results, and explanations are seamlessly integrated. It's a key feature of R Markdown for reproducible research and data analysis reporting.
