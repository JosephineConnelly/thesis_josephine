---
title: "Thesis Part 2"
date: "2023-05-17"
author: "Josephine Estelle Ananda Connelly"
bibliography: "bibliography.bib"
link-citations: true
urlcolor: "blue"
---

# make .md Make into .docx

pandoc -o output.docx -f markdown -t docx textfile.md

with bib
pandoc -o output.docx -f markdown -t docx --bibliography=bibliography.bib --csl=citation-style.csl textfile.md


pandoc -s input.docx -o output.md

# Abstract

# Introdution

# Results
some kind of overall results 
H1
the pca, the dendogram the fst the Maf...
collect the data in a table






# Methods

# Conclusion

# References