# carbonlabel — Visualize <sup>13</sup>C labeled molecules in LaTeX
`carbonlabel` is a LaTeX package that draws simple molecules with <sup>13</sup>C labeled carbon atoms.

**The package is currently under heavy development and not intended for productive usage!**

Simple example:
```latex
\documentclass{minimal}
\usepackage{carbonlabel}
\begin{document}

% 6 atoms, 2 per row, uniformly 13C labeled
\labeling{2,2,2}{u} [U-\textsuperscript{13}C] Glucose
\\[.5cm]
% 6 atoms, in one row, 1,2-13C labeled
\labeling{6}{1,2}  [1,2-\textsuperscript{13}C] Glucose

\end{document}
```
Produces:

![carbonlabel exaple output](http://i.imgur.com/Ra8sWAq.png)

