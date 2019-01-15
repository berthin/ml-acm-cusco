# Intructions

Lecture information can be edited in this section:

```tex
% LECTURE INFORMATION
\title{ML week slides template}
\institute{EEPP IIS-UNSAAC}

\author{Lecturer name\\
        lecturer mail}

\date{\today}
```

Lecture slides start here, start editing after `\section{Ejemplo de sección 1}`.

```tex
% SLIDES EXAMPLE STARTS HERE 
\begin{document}
%cover of slides
\frame{\titlepage}
%table of contents
\begin{frame}
    \frametitle{Contenido}
    \footnotesize{
    \tableofcontents
    }
\end{frame}

%start editing here
\section{Ejemplo de sección 1} % ----------------------------------
\subsection{Ejemplo de subsección 1}
\begin{frame} 
   \frametitle{Ejemplo de título 1}

```

In order to generate pdf run:

```bash
make
```
or

```
pdflatex slides
```

