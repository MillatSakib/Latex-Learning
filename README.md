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
