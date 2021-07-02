# Project name

UAP Data Recording Model (DRM), an [UAP initiative](https://www.uap-initiative.org) 
project.

# Description

This project aims to define a data recording model which describes components and
links in UAP's sightings files.

This work will provide the base on which our client-server application will be
developped.

This consists of editing the source files of web pages and source files of schemas
and diagrams.

# Installation

We propose to work with [Graphviz](https://graphviz.org/) and
[Plantuml](https://plantuml.com/en/) to produce graphs and diagrams.

> _Graphviz is open source graph visualization software. The Graphviz layout
> programs take descriptions of graphs in a simple text language, and make
> diagrams in useful formats, such as images and SVG for web pages; PDF or
> Postscript for inclusion in other documents; or display in an interactive
> graph browser. Graphviz has many useful features for concrete diagrams,
> such as options for colors, fonts, tabular node layouts, line styles,
> hyperlinks, and custom shapes._

> _PlantUML is a component that allows to quickly write diagrams. Diagrams
> are defined using a simple and intuitive language. New users can read the
> quick start page. Images can be generated in PNG, in SVG or in LaTeX
> format. It is also possible to generate ASCII art diagrams (only for
> sequence diagrams)._

_Pandoc_ converts files from a format into an another one. Very usefull to
convert markdown files into `*.html`.

_Pdflatex_ should be used later to produce a smart reference document but at
this time, we suggest the use of markdown files `*.md` that don't require any
specific application.

# Usage

Edit `*.md`, `*.dot` and `*.uml` files with a text editor (Vim, GVim, Notepad++,
Atom, etc.).

You can _locally_ generate :

- `*.dot` graphs using Graphviz ;
- `*.uml` diagrams using Plantuml ;
- `*.html` pages from `*.md` files using Pandoc.

For more details about these apps usage, please refer to their documentation.
Here is some direct links :

- [Vim](https://www.vim.org/docs.php)
- [Atom](https://flight-manual.atom.io/)
- [Plantuml](https://plantuml.com/en/)
- [Graphviz](https://graphviz.org/documentation/)
- [Pandoc](https://pandoc.org/getting-started.html)

# Contributing

This project is open to contributors !

We need your help to :

- define concepts to describe components in an UAP sighting case and links
  between them ;
- write the related documentation ;
- document related processes to these concepts ;
- correct and complete the _database model for UAP's sightings record_ ;
- correct spelling, improve graphs and diagrams's layout.

More instructions and tips : please see [CONTRIBUTING](CONTRIBUTING.md) and
[CODE OF CONDUCT](CODE_OF_CONDUCT.md).

# License
Unless otherwise stated, elements shared in this repository are licensed under CC BY-SA 4.0.
