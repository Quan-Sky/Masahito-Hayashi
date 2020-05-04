---
title: Analysis of Practical Quantum Key Distribution Systems
type: topic
layout: research
---



Quantum key distribution (QKD) is the theoretical proposal that is close to realisation in quantum information science. 
While an ideal QKD system is secure, 
the security of a realisable QKD system requires additional protocols and more careful discussion 
because of the many kinds of imperfections, e.g., noise of the quantum channel and imperfection of photon source. 
%Due to these imperfections, 
We need to attach error correction and privacy amplification to the conventional QKD protocol. Further, imperfection in photon sources introduces additional channel parameters that should be estimated.

Based on my work on wire-tap channels 
[IEEE TIT \textbf{52} 1562 (2006), \cite{Ha03b} of \textbf{C3}], %50
% IEEE TIT \textbf{57} 3989 (2011)]. %29
I developed a concrete and secure QKD protocol with small calculation time
while existing researches offered no such concrete protocol
[PRA \textbf{76} 012329 (2007)]. %57
Many implemented QKD systems utilise this protocol. 
The first essential point was to propose a protocol 
for privacy amplification by modifying a Toeplitz matrix whose calculation time is linear in the block size $n$ 
[PRA \textbf{76} 012329 (2007)]. 
Second, I proposed a method to perfectly estimate the additional channel parameters
whereas existing methods only estimated it partially 
[NJP \textbf{9} 284 (2007) \& \cite{Hp8} of \textbf{C2}]. %20
As a result of this improvement, the key generation rate was extensively improved. 
Third, I clarified the amount of leaked information and derived the sacrificed bit length required for an arbitrary desired security 
level for the estimated channel parameters in 
the finite-block-size setting 
[PRA \textbf{74} 022307 (2006) %39
\& PRA \textbf{76} 012329 (2007)] by using the trade-off between accessible information and quantum disturbance 
[PRL \textbf{100} 210504 (2008), \cite{BHH08} of \textbf{C3} ]. %23
Finally, in cooperation with the above channel parameter estimation, I derived a calculation formula for the sacrificed bit length with the form applicable to the realised QKD system 
[NJP \textbf{14} 093014 (2012), \cite{HT12} of \textbf{C2} \& \cite{Hp8} of \textbf{C3}]. %3
%in preparation]. 
Using this formula, I addressed the trade-off between cost and accuracy for the estimation of leaked information 
[PRA \textbf{79} 020303(R) (2009), \cite{Ha09-1} of \textbf{C2}]. %4
This formula was chosen for use in the implemented QKD system by this project in Japan, 
which will be demonstrated over an installed optical fibre
because my analysis satisfies all practical and experimental requirements for the NICT project.

According to Google Scholar, this research has been cited \textbf{\textit{225}}
 %50+29+57+20+39+23+3+4
 times since 2006.



\renewcommand{\refname}{}
\vspace{-20 mm}
\begin{thebibliography}{99}
\bibitem[\textbf{References}]{r0}

\bibitem[PRA \textbf{76} 012329 (2007)]{r1} 
\textbf{M. Hayashi},
%\textbf{M. Hayashi}, 
``Upper bounds of eavesdropper's performances in finite-block-size coding with the decoy method,'' 
{\em Physical Review A}, Vol. 76, 012329 (2007).

\bibitem[NJP \textbf{9} 284 (2007)]{r2}
\textbf{M. Hayashi},
%\textbf{M. Hayashi}, 
``General theory for decoy-state quantum key distribution with an arbitrary number of intensities,'' 
{\em New Journal of Physics}, Vol. 9, 284 (2007).

\bibitem[PRA \textbf{74} 022307 (2006)]{r3}
\textbf{M. Hayashi},
%\textbf{M. Hayashi}, 
``Practical evaluation of security for quantum key distribution,'' 
{\em Physical Review A}, Vol. 74, 022307 (2006).