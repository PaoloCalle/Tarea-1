\documentclass{article}
\usepackage{graphicx} % Required for inserting images
\usepackage{amsmath} % Para matemáticas avanzadas
\usepackage{ulem} % Para subrayado
\usepackage{xcolor} % Para color en texto y más

% Configuración de los márgenes de la página
\usepackage[a4paper, margin=2.5cm]{geometry}

% Configuración de los encabezados de las secciones
\usepackage{titlesec}
\titleformat{\section}[block]{\large\bfseries\filcenter}{\thesection}{1em}{}

\title{Jjjji}
\author{Paolo Calle}
\date{April 2024}

\begin{document}

\maketitle % Esto crea el título basado en la información anterior

\section*{\uline{1.1.1 Medida}} % Subraya el título de la sección
% Descripción de espacio medible
\noindent\textbf{Espacio Medible:} Por espacio medible entendemos un par ordenado $(\Omega, B)$ que consta de un conjunto $\Omega$ y un $\sigma$-álgebra $B$ de subconjuntos de $\Omega$. Un subconjunto $A$ de $\Omega$ se llama medible si $A \in B$.

% Descripción de medida
\noindent\textbf{Medida $\mu$:} Una medida $\mu$ en un espacio medible $(\Omega, B)$ es una función definida como sigue:
\begin{equation}
\begin{aligned}
\mu(\emptyset) &= 0 \\
\mu\left(\bigcup_{i=1}^{\infty} E_i\right) &= \sum_{i=1}^{\infty} \mu(E_i)
\end{aligned}
\end{equation}
para cualquier sucesión $\{E_i\}$ de conjuntos medibles disjuntos, es decir, $E_i \cap E_j = \emptyset$ para $i \neq j$ y cada $E_i \in B$.

% Descripción de espacio de medida
\noindent\textbf{Espacio de Medida:} $(\Omega, B, \mu)$ se denomina espacio de medida.

\end{document}
