---
title: Quantum Universal Protocols with Group Symmetries
type: topic
layout: research
---



Quantum information has several information protocols, e.g., quantum source coding, quantum channel coding, and perfect entangled state generation from partial entangled states. 
Existing protocols depend on the parameters that describe the quantum information source and the quantum channel. 
However, it is quite difficult to identify these parameters in a quantum system.
Even if it is possible, the identification of the parameters may cause information loss due to the state reduction by measurement. 
Hence, protocols are required that universally work independently of these parameters. 
Using the method of types, 
Csiszar and K\"{o}rner [\emph{Information Theory: Coding Theorems for Discrete Memoryless Systems}, Akad\'emiai Kiad\'o (1981)]
proposed universal protocols for classical source coding and classical channel coding. 
By contrast, in quantum systems, quantum universal protocols are required to have basis independence.
Hence, we cannot directly apply the original type method to quantum systems because 
the original type method can work only with an specific basis.
%In quantum systems, the universal protocols are required to works independently of the coordinate.
%However, to apply the original type method to quantum systems directly, we have to choose a basis.

%To resolve this problem, I remembered that
%the group representation theory enables us to treat physical properties independent of the coordinate.
I showed that the group representation theory can greatly simplify 
quantum state estimation with the $n$-copy case
by removing the basis dependence
[JPA \textbf{31} 4633 (1998)]. %27
%\& JPA \textbf{33} 7793 (2000)]. %9
%Physics Reports, \textbf{448} 1 %107 
%Proc. QCMC 2, 99 (2002) %7
%JMP 49 102101 (2008) %33
%JPA 35 7689 (2002) %30   
I then found a quite unexpected and remarkable similarity between the Schur duality in the group representation theory and the method of types
%[JPA \textbf{34} 3413 (2001) %19 \& 
[JPA \textbf{35} 10759 (2002)]. %38
Based on this discovery, I invented quantum universal protocols for all of the above quantum coding problems 
%[PRA \textbf{66} 022311 (2002), %41
%PRA \textbf{66} 032321 (2002), %15
%QIC \textbf{2} 519 (2002), %16
%PRA \textbf{75} 062338 (2007), %16
[CMP \textbf{289} 1087 (2009), \cite{Ha09-4} of \textbf{C2} \& %9
CMP \textbf{293} 171 (2010), \cite{Ha09-7} of \textbf{C2}]. %5
Thanks to these protocols, we can now choose our protocol without knowledge of the parameters of 
quantum information sources or channels. 
This property enables us to avoid additional measurements to identify the quantum system. 
In particular, using irreducible representation theory, I realised basis independence for the above protocols. 
I also guaranteed their performance by the sophisticated use of matrix inequalities.

I subsequently applied these techniques 
to the problem of distinguishing multi-partite entangled states [PRL \textbf{96} 040501 (2006), \cite{HMMOV03} of \textbf{C3}]. %102
%PRA \textbf{77} 012104 (2008) %55 
%JMP \textbf{50} 122104 (2009) %25
%NJP \textbf{12} 083002 (2010)]. %13
Since multi-partite entanglement is related to multi-user communication, in particular, to quantum networks 
[PRA \textbf{76} 040301(R) (2007)], % 17
%LNCS \textbf{4393} 610 (2007)], %26
these results are helpful for this project. 

According to Google Scholar, this research has been cited \textbf{\textit{610}}  
%27+9+107+7+33+30+19+38+41+15+16+16+9+5+102+55+25+13+17+26
times since 1998.

\renewcommand{\refname}{}
\vspace{-20 mm}
\begin{thebibliography}{99}
\bibitem[\textbf{References}]{s0}

\bibitem[JPA \textbf{31} 4633 (1998)]{s1} 
\textbf{M. Hayashi},
%\textbf{M. Hayashi}, 
``Asymptotic estimation theory for a finite dimensional pure state model,'' 
{\em Journal of Physics A: Mathematical and General}, Vol. 31, No. 20, 4633-4655 (1998).

\bibitem[JPA \textbf{35} 10759 (2002)]{s2}
\textbf{M. Hayashi},
%\textbf{M. Hayashi}, 
``Optimal sequence of quantum measurements in the sense of Stein's lemma in quantum hypothesis testing,'' 
{\em Journal of Physics A: Mathematical and General}, Vol. 35, No. 50, 10759-10773 (2002).

\bibitem[PRA \textbf{76} 040301(R) (2007)]{s3}
\textbf{M. Hayashi},
%\textbf{M. Hayashi}, 
``Prior entanglement between senders enables perfect quantum network coding with modification,'' 
{\em Physical Review A}, Vol. 76, 040301(R) (2007).

\end{thebibliography}