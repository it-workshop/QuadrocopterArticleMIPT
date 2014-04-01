cmake_minimum_required(VERSION 2.8)
project(hcp-pottest-paper)

include(${CMAKE_ROOT}/Modules/UseLATEX.cmake)
set(IMAGES "./images")

#set(PDFLATEX_COMPILER xelatex)
set(LATEX_OUTPUT_PATH "${CMAKE_BINARY_DIR}")

ADD_LATEX_DOCUMENT(paper.tex
    INPUTS
    skel.tex
    #00-abstract.tex
    #01-introduction.tex
    #02-motivation.tex
    #03-methodology.tex
    #04-results.tex
    #05-closure.tex
    IMAGE_DIRS ${IMAGES}
    #BIBFILES references.bib
    DEFAULT_PDF)
