# Michelle Jamieson Academic CV

## Enhancements Compared to the default `vitae` package:

* Styling publications using given csl file in `YAML`.
* Printing as many bibliographic sections and corresponding entries as you want in your CV (e.g., journal publication, conference proceedings, software developments, etc. etc.).
* Highlighting your name in printed bib entries using bold format (see and change the content in `lua/strong.lua`).
* Easily scraping education and publication history from ORCID and/or Google Scholar, so you only have to keep one place updated.


## Description

This repo has been created to systematically manage my academic CV. This is reproducible for those who have basic knowledge of R and R Markdown.

Based on [vitae package](https://github.com/mitchelloharawild/vitae/), I have extended its capabilities to include multiple bibliographic entries using [multiple-bibliographies lua filter](https://github.com/pandoc/lua-filters/blob/master/multiple-bibliographies/multiple-bibliographies.lua) so that I can print my scientific records in [APA_CV style](https://github.com/citation-style-language/styles/blob/master/apa-cv.csl).

Following my template, you would be able to print as many bib-entries as you want using your desired csl file and your `*.bib` files.
