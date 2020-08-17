[![made-with-latex](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/) [![GPL license](https://img.shields.io/badge/License-GPL-blue.svg)](http://perso.crans.org/besson/LICENSE.html) 

# beamer-themes

A hopefully growing collection of (latex) beamer-themes that i have created over the years. All themes supplied are standalone versions.

## General

Some resources are shared between all of the example-documents (they are just placeholders and therefore not necessary).
The example bibliography-file is based on an [overleaf-example](https://www.overleaf.com/learn/latex/Bibliography_management_in_LaTeX).

## colorful-dream

This theme is located [here](./colorful-dream) and _has_ BibLaTeX-Support.
Valid Options (defaults are marked):

- `nofont`/__`font`__ (automatic font-loading)
- `nolibs`/__`libs`__ (automatic loading of other libraries like tikz)
- __`noemblem`__/`emblem` (place emblem on titlepage, configure the emblem with `\SetEmblem`)
- __`notheorems`__/`theorems` (automatic configuration of theorems. Will define "exercise" and "solve").

Other configuration-options and commands like `\email` and `\outro` are presented in the [example.tex](colorful-dream/example.tex):

![colorful-dream example image](colorful-dream/example.png)
