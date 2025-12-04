latex-homework-template 
=======================

## features

1. Seperate the template into two parts: `homework.tex` and `homework_problems.tex`.
2. Add some new command for maths.
   ```tex
   \newcommand{\solution}{\textbf{\large Solution}}

   \newcommand{\R}[1]{\ensuremath{\mathbb{R}}^{#1} }
   \newcommand{\N}[1]{\ensuremath{\mathbb{N}}^{#1} }
   \newcommand{\Z}[1]{\ensuremath{\mathbb{Z}}^{#1} }
   \newcommand{\Q}[1]{\ensuremath{\mathbb{Q}}^{#1} }

   \newcommand{\cl}[1]{\ensuremath{\mathcal{#1}} }

   % zero vector
   \newcommand{\zv}{\ensuremath{\mathbf{0}} }
   \newcommand{\x}{\ensuremath{\mathbf{x}} }
   \newcommand{\y}{\ensuremath{\mathbf{y}} }
   \newcommand{\z}{\ensuremath{\mathbf{z}} }
   \newcommand{\veca}{\ensuremath{\mathbf{a}} }
   \newcommand{\vecb}{\ensuremath{\mathbf{b}} }
   \newcommand{\vecc}{\ensuremath{\mathbf{c}} }
   \newcommand{\vecu}{\ensuremath{\mathbf{u}} }
   \newcommand{\vecv}{\ensuremath{\mathbf{v}} }
   \newcommand{\vecw}{\ensuremath{\mathbf{w}} }

   % \newcommand{\det}{\ensuremath{\mathrm{det}}}
   \newcommand{\pdet}[1]{\ensuremath{\mathrm{det} \left( #1 \right)} }
   % \newcommand{\dim}{\ensuremath{\mathrm{dim}}}
   \newcommand{\pdim}[1]{\ensuremath{\mathrm{dim} \left( #1 \right)} }
   \newcommand{\rank}{\ensuremath{\mathrm{rank}}}
   \newcommand{\prank}[1]{\ensuremath{\mathrm{rank} \left( #1 \right)} }
   \newcommand{\nul}{\ensuremath{\mathrm{Nul}}}
   \newcommand{\pnul}[1]{\ensuremath{\mathrm{Nul} \left( #1 \right)} }
   \newcommand{\col}{\ensuremath{\mathrm{Col}}}
   \newcommand{\pcol}[1]{\ensuremath{\mathrm{Col} \left( #1 \right)} }
   \newcommand{\row}{\ensuremath{\mathrm{Row}}}
   \newcommand{\prow}[1]{\ensuremath{\mathrm{Row} \left( #1 \right)} }
   % \newcommand{\span}{\ensuremath{\mathrm{span} \left{ #1 \right}}}
   \newcommand{\adj}{\ensuremath{\mathrm{adj}} }
   \newcommand{\padj}[1]{\ensuremath{\mathrm{adj} \left( #1 \right)} }
   \newcommand{\tr}{\ensuremath{^{T}} }

   \newcommand{\pd}{\ensuremath{\partial}}

   \newcommand{\pmat}[1]{\ensuremath{\begin{pmatrix}#1\end{pmatrix}} }  % Parentheses
   \newcommand{\bmat}[1]{\ensuremath{\begin{bmatrix}#1\end{bmatrix}} }  % Square brackets
   \newcommand{\Bmat}[1]{\ensuremath{\begin{Bmatrix}#1\end{Bmatrix}} }  % Curly braces
   \newcommand{\vmat}[1]{\ensuremath{\begin{vmatrix}#1\end{vmatrix}} }  % Single vertical line (determinant)
   \newcommand{\Vmat}[1]{\ensuremath{\begin{Vmatrix}#1\end{Vmatrix}} }  % Double vertical line (norm)

   \newcommand{\covec}[3]{\ensuremath{\left[ \mathbf{#1}_{#2} \right]_{\mathcal{#3}}}} 

   % change-of-coordinates matrix from standard basis to #1
   \newcommand{\chco}[1]{\ensuremath{P_{\mathcal{#1}}}}

   % change-of-coordinates matrix from #1 to #2
   \newcommand{\cchco}[2]{\ensuremath{\underset{\mathcal{#2} \leftarrow \mathcal{#1}}{P}}}
   ```