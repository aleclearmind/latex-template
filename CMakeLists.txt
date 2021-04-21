cmake_minimum_required(VERSION 3.7)
project(latex_document NONE)

include(UseLATEX.cmake)
add_latex_document(main.tex
  BIBFILES biblio.bib
  INPUTS
  plain.bst
  main.tex
  )
