#
# Example Makefile for Unix(-like) systems with pdflatex
# 

default:
	pdflatex -halt-on-error -interaction=nonstopmode example.tex
	pdflatex -halt-on-error -interaction=nonstopmode example.tex

	pdflatex -halt-on-error -interaction=nonstopmode example2.tex
	pdflatex -halt-on-error -interaction=nonstopmode example2.tex
	biber example2
	pdflatex -halt-on-error -interaction=nonstopmode example2.tex
	pdflatex -halt-on-error -interaction=nonstopmode example2.tex
