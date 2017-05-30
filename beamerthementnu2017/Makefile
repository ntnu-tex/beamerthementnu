#
# Example Makefile for Unix(-like) systems with pdflatex
# 

default:
	pdflatex -halt-on-error -interaction=nonstopmode example.tex
	pdflatex -halt-on-error -interaction=nonstopmode example.tex
	biber example
	pdflatex -halt-on-error -interaction=nonstopmode example.tex
	pdflatex -halt-on-error -interaction=nonstopmode example.tex
