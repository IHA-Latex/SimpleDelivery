# SimpleDelivery

This is a template for making a simple delivery.
It is written in LaTeX and will use the ```documentclass{article}```.

The outlines for using article is as follow:
* ```\section{Heading 1}```
* ```\subsection{Heading 2}```
* ```\subsubsection{Heading 3}```
* ```\paragraph{Heading 4}``` (remember the Paragraph.tex) to give you a linebreak after the heading.


* ```\title{The title}``` (in the preamble)
* ```\author{Name of author(s)}``` (in the preamble)
* ```\date{Date of delivery}``` (in the preamble)
* ```\maketitle``` (right after ```\begin{document}```)


## The structure

When organizing your files, you can use the following structure:
+ Documents/
  + Assignment/
    - As1.tex
    - As2.tex
    - Main.tex
    - Preamble.tex
    - ...
  + Figures/
    - Dummy.png
    - ...
  + LatexModules
    - *.tex
    - ...

## LatexModules
The [LatexModules](https://github.com/Limro/LatexModules) is a repository with a lot of small packages and configurations of these, which makes it easy to get starting with writing a document.

To use these you first fork the project to your own organization / account.
After this you clone it and must update the submodules:

```git
git clone #git@github.com:Organization/Name.git LocalFolderName
git submodule init
git submodule update
```

