---
title: 'libtrixi: an interface library for using Trixi.jl from C/C++/Fortran'
tags:
  - numerical simulation
  - Julia
  - cross-language interoperability
authors:
  - name: Michael Schlottke-Lakemper
    orcid: 0000-0002-3195-2536
    corresponding: true
    affiliation: "1, 2" # (Multiple affiliations must be quoted)
  - name: Benedict Geihe
  - orcid: 0000-0002-9519-6872
    affiliation: 3
  - name: Gregor J. Gassner
    orcid: 0000-0002-1752-1158
    affiliation: 3
affiliations:
 - name: Applied and Computational Mathematics, RWTH Aachen University, Germany
   index: 1
 - name: High-Performance Computing Center Stuttgart (HLRS), University of Stuttgart, Germany
   index: 2
 - name: Department of Mathematics and Computer Science, University of Cologne, Germany
   index: 3
date: 26 September 2023
bibliography: paper.bib
---

# Summary

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Trixi.jl [@schlottkelakemper2020trixi]

# Statement of need

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat
cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


# Mathematics

Single dollars ($) are required for inline mathematics e.g. $f(x) = e^{\pi/x}$

Double dollars make self-standing equations:

$$\Theta(x) = \left\{\begin{array}{l}
0\textrm{ if } x < 0\cr
1\textrm{ else}
\end{array}\right.$$

You can also use plain \LaTeX for equations
\begin{equation}\label{eq:fourier}
\hat f(\omega) = \int_{-\infty}^{\infty} f(x) e^{i\omega x} dx
\end{equation}
and refer to \autoref{eq:fourier} from text.

# Citations

Citations to entries in paper.bib should be in
[rMarkdown](http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html)
format.

If you want to cite a software repository URL (e.g. something on GitHub without a preferred
citation) then you can do it with the example BibTeX entry below for @fidgit.

For a quick reference, the following citation commands can be used:
- `@author:2001`  ->  "Author et al. (2001)"
- `[@author:2001]` -> "(Author et al., 2001)"
- `[@author1:2001; @author2:2001]` -> "(Author1 et al., 2001; Author2 et al., 2002)"

# Figures

Figures can be included like this:
![Caption for example figure.\label{fig:example}](figure.png)
and referenced from text using \autoref{fig:example}.

Figure sizes can be customized by adding an optional second parameter:
![Caption for example figure.](figure.png){ width=20% }

# Acknowledgements

This project has benefited from funding by the Deutsche Forschungsgemeinschaft (DFG, German
Research Foundation) through the research unit FOR 5409 "Structure-Preserving Numerical
Methods for Bulk- and Interface Coupling of Heterogeneous Models (SNuBIC)" (project number
463312734), and DFG individual grant number 528753982.

This project has benefited from funding from the German Federal Ministry of Education and
Research through the project grant "Adaptive earth system modeling with significantly
reduced computation time for exascale supercomputers (ADAPTEX)" (funding id: 16ME0668K).

# References
