TemplateBeamer
=============

## Installazione
Clonare la cartella della repository in questo path:

*Fedora -> /usr/share/texlive/texmf-dist/tex/latex*

*Mac OS -> /usr/local/texlive/2014/texmf-dist/tex/latex*

*Ubuntu -> /usr/share/texmf/tex/latex*

Comandi da utilizzare dopo aver creato la cartella:

*sudo mktexlsr*

*sudo texhash*

## Come usarla

Inizio documento Latex

```
\documentclass{beamer}
\usepackage{perugiabeamer}

\title{titolo tesi}
\author{
	Candidato:  \\
	Relatore:  
\bigskip}
\date{}

\begin{document}
	\addoutline
	\maketitle

\end{document}

```

Ogni slide viene scritta come segue:
```
\begin{frame}
\frametitle{titolo slide}


\end{frame}
```
