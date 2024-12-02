# LaTex Code:

## Basic code of LaTex:

```tex
\documentclass{article}
\usepackage{graphicx} % Required for inserting images

\title{Programming with YoutubeUniversity}
\author{Md. Sohan Millat Sakib}
\date{December 2024}

\begin{document}

\maketitle      % Automatically show title, Athor and Date of document for this command
\vspace{-5mm} % Remove extra space
\begin{center}
    My name is Sohan Millat Sakib, a student\\ of Green University of Bangladesh
    %use \\ for add a new line
\end{center}


\section{Introduction}
\section{Data Tyepes}
\subsection{Premitive}
\subsubsection{Number}
\subsection{Non Premitive}
\section{Operators}
\end{document}


```

Output:

![basicCode](./src/baiscCode.png)

## Font Control:

Here we will learn how can we change different parameter of font or text.

```tex
\documentclass{article}

\title{Programming with YoutubeUniversity}
\author{Md. Sohan Millat Sakib}
\date{December 2024}

\begin{document}

\maketitle
\vspace{-5mm}
\section{Bangladesh}
\large
\textbf{Bangladesh is a small and beautiful country in South Asia.\\} %this is for make bold font

\small
\textit{We get independence in 1971 from Pakistan after a long war.\\}  %this is for make italic font

\huge
\underline{Because of the sacrifice of millions of freedom fighters.\\}

\large
\textbf{textit{16 December is our Victory Dasy because this day Pakistani army surrenderd}}

\tiny
Don't wory. This is tiny text.

\end{document}

```

Output:

![basicCode](./src/fontControl.png)

## Use Special Keywords

There have some special keyword in LaTex which are use in defferent purpose like `%`, `$`, `#`. If we try to use this keywords we got error form compiler. That's why we have to use `escape sign` for this. On the other hand sometime we have to use `copyright` or `registered` symbol. We can also make them using this escape charecter.

```tex
\documentclass{article}
\usepackage{graphicx} % Required for inserting images

\title{Programming with YoutubeUniversity}
\author{Md. Sohan Millat Sakib}
\date{December 2024}

\begin{document}

\maketitle
\section{Apple Company}
The company shares fell just over 2\% on Monday to close at \$175.74, reversing earlier gains that saw them aproach the \$182.86 price needed to record a \$3 trillion market value.
% using escape charecter for % and $

\# \\  % using escape charecter for #
\copyright\\
\textregistered   % using escape charecter for those symbol

\end{document}

```

Output:

![basicCode](./src/escapeCharecter.png)

## Alignment & Layout

```tex
\documentclass{article}
\usepackage[a4 paper, landscape]{geometry} % import packagge for page setup

\title{Programming with YoutubeUniversity}
\author{Md. Sohan Millat Sakib}
\date{December 2024}

\begin{document}
\maketitle


\begin{flushleft}   % This is for left alignment
WorldCuup FootBall Quatar 2024
\end{flushleft}

\begin{flushright}    % This is for right alignment
WorldCuup FootBall Quatar 2024
\end{flushright}

\begin{center}     % This is for center alignment
WorldCuup FootBall Quatar 2024
\end{center}

\end{document}
```

Output:

![basicCode](./src/alignmentAndLayout.png)

## List

Here All type of list code are available. Please follow the code below:

```tex
\documentclass{article}
\usepackage{paralist} % this package is for the list which will contain side by side
\usepackage{enumitem}  % this package is for making the custom item list
\title{Programming with YoutubeUniversity}
\author{Md. Sohan Millat Sakib}
\date{December 2024}

\begin{document}
\maketitle

\section{Football}
\begin{itemize}
    \item Brazil
    \item Arzentina
    \item Japan
    \item Ghana
\end{itemize}

\section{Cricket}
\begin{enumerate}
    \item Bangladesh
    \begin{itemize}
        \item Shakib
        \item Tamim
        \item Rony
    \end{itemize}
    \item India
    \item USA
    \item USB
\end{enumerate}

\section{Foods}     % this are works for importing paralist package
\begin{inparaenum}
\item apple
\item orange
\item tea
\end{inparaenum}

\section{Country}  %this are works for enumitem package
\begin{enumerate}[label=\alph*.]
    \item Bangladesh
\end{enumerate}


\section{Country}
\begin{enumerate}[label=\alph*.]
    \item Bangladesh
\end{enumerate}


\section{Country}
\begin{enumerate}[label=\roman*.]
    \item Bangladesh
\end{enumerate}

\section{Country}
\begin{enumerate}[label=\roman*.,start = 3]
    \item Bangladesh
\end{enumerate}


\end{document}

```

Output:

![basicCode](./src/item1.png)
![basicCode](./src/item2.png)
