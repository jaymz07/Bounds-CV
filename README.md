# James R. Bounds Curriculum Vitae

This repository contains the LaTeX source for my academic curriculum vitae.

## View the CV

[Bounds CV](./BOUNDS - CV.pdf)

## Building

Compile with

latexmk -pdf CV.tex

or

lualatex CV.tex
biber CV
lualatex CV.tex
lualatex CV.tex

depending on your TeX workflow.

## Requirements

- TeX Live 2025 or newer
- biblatex
- biber
