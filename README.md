perugiabeamer
=============

Inizio documento Latex

```
\pdfminorversion 4
\documentclass{beamer}
\usepackage{perugiabeamer}

\title{titolo tesi}
\author{Candidato:  \\
		    Relatore:  \bigskip}
\date{}

\begin{document}
	\frametitle{}
	\maketitle

\end{document}

```

Ogni slide viene scritta come segue:
```
\begin{frame}
\frametitle{titolo slide}


\end{frame}
```

Per aggiungere il nome della sezione sopra al titolo delle slide scrivere `\addsectionname` appena sotto a `\begin{document}`
