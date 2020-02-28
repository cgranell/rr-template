# rr-template
A template project structure for reproducible research (RR) projects.

This repo is designed to make reproducible research projects easy. It has a basic project folder structure and follwos an easy to remember naming convention:

  * [data-raw](data-raw/): all input data (and metadata) used in the project. _Note: Same name as data packages in R_
  * [data](data/): intermediate or output data files (e.g. simulation outputs, processed data, cleaned data).
  * [figs](figs/): figures generated by the analysis.
  * [R](R/): R scripts with function definitions.
  * [notes](notes/): keep track of ideas, rationale, concerns, dicussion adn decision abiut the analysis/projects.
  * [doc](doc/): manuscript or scientific article. 
  * [reports](reports/): RMarkdown or Markdown files that document the analysis (e.g. reproducible reports). 
  * [webapp](webapp/): prototype(s) of Shiny web apps. When it goes into production, it should be in a separate repo.
  * README.Rmd: the document you are reading.
  * LICENCE: licence file.
 
