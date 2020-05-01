---
title: Information Spectrum and Finite-block-size Analysis in Classical and Quantum Information
type: topic
layout: research
---



Consider the problem of transmitting classical information via classical noisy channels as a typical problem in information theory. This problem is called classical channel coding, and it is possible to describe the optimal performance of channel coding in the asymptotic limit concerning the block-size of codes as Shannon's channel-coding theorem, bur, in any real communication system, we can only use codes with finite block-size. Hence, it is necessary to estimate the optimal coding length $L_{\epsilon,n}$ among codes with block-size $n$ for a given allowable error probability $\epsilon>0$. In fact, the traditional asymptotic analysis does not work for this problem for the following reason.
In Shannon's channel-coding theorem, the asymptotic limit $\lim_{n \to \infty} L_{\epsilon,n}/n$ is treated as the channel capacity. However, the limit does not give a good approximation of $L_{\epsilon,n}$ %with block-size $n$ and $\epsilon>0$ because the convergence is quite slow.  The reason for the inadequacy of the convergence is that the limit value does not reflect the error probability $\epsilon$, not uniform with respect to $\epsilon$, which is caused by the independence of $\epsilon$. Therefore, a good approximation for $L_{\epsilon,n}$ is required.

This problem becomes more serious in quantum communication because the quantum key distribution (QKD) system works only with finite-block-size codes. We cannot apply the result from the asymptotic theory directly to implemented QKD systems. 


To derive a better approximation, I considered the asymptotic expansion of $L_{\epsilon,n}$ up to the second order $\sqrt{n}$ as $L_{\epsilon,n}\cong L_1 n+ L_{2,\epsilon}\sqrt{n}$ because the second order coefficient $L_{2,\epsilon}$ properly reflects the error probability $\epsilon$, so that the difference between $L_{\epsilon,n}$ and $L_1 n+ L_{2,\epsilon}\sqrt{n}$ is not so large.
Employing the information spectrum method, I derived the second order coefficient for 
classical channel coding as well as other many kinds of settings
which contain source coding, channel coding, and secure random number extraction 
[IEEE TIT \textbf{54} 4619 (2008), \cite{Ha08b-1} of \textbf{C3}]. %41
%Those results directly give the approximation of the optimal coding length with block-size $n$.
Indeed, although the existing result could solve only the discrete memoryless case for channel coding, 
my result applied to classical channel coding covers 
the Gaussian channel case, the energy constraint case and the Markovian case 
[IEEE TIT \textbf{55} 4947 (2009), \cite{Ha09b} of \textbf{C3}] %41
as well as the discrete memoryless case. 
The information spectrum method addresses only the logarithmic likelihood (ratio) for channels or sources, 
and does not consider the other properties of channels or sources. 
Since the analysis by this method is concentrated on the treatment of the logarithmic likelihood (ratio),
the method provides a unified viewpoint on several topics in information theory.
Thanks to the generality of the method, 
I succeeded in calculating the second order coefficients of the above problems.
%The simplicity of the derivation is clear because of the shortness of the total page lengths and the wideness of areas covered by two papers. 
%In particular, 
The paper [IEEE TIT \textbf{55} 4947 (2009), \cite{Ha09b} of \textbf{C3}] was awarded 
the 
\textbf{\textit{2011 IEEE Information Theory Society Paper Award}}.
This award is presented to one or two of the most significant information theory papers worldwide by the IEEE Information Theory Society. 
Papers awarded this prize are among the most significant and ground-breaking in their year.

Indeed, the topic itself concerns the classical case. 
However, as mentioned in the first paragraph, the problem becomes more serious in the quantum case.
To resolve this problem in the quantum case, I first solved this problem in the classical case.
To address the quantum case,
I established the information spectrum method in quantum systems 
[IEEE TIT \textbf{49} 1753 (2003), \cite{HN03b} of \textbf{C3}] %113
%IEEE TIT \textbf{52} 1562 (2006), %13
%\& IEEE TIT \textbf{53} 534 (2007)] %49
%[\textbf{M. Hayashi}, {\em Quantum Information: An Introduction}, Springer (2006)] 194
with Nagaoka.
%In particular, 
We derived a novel matrix inequality for this purpose, 
which has often been referred to as the
``Hayashi-Nagaoka inequality'' in many papers for quantum channel coding.
We then applied it to the quantum setting and solved the problem of the second order coefficients 
in several quantum cases [QIP 2013, \cite{THc13-1} of \textbf{C2}].%4

The next problem was to derive the upper and lower bounds of the optimal coding length with block-size $n$ 
that attains the above optimal second order coefficient in the asymptotic sense. 
We can easily derive such upper and lower bounds if we are not concerned about the complexity.
However, the computability of bounds is required, as well as the tightness of bounds.
The essential point is the trade-off between the approximation error and the complexity. 
To clarify the trade-off, 
we proposed several upper and lower bounds, and demonstrated their hierarchy. 
%That is, more precise bound requires more calculation time.
Employing the hierarchy, we clarified which bound is most 
useful when the block-size $n$ is sufficiently large [QIP 2013, \cite{THc13-1} of \textbf{C2}].

According to Google Scholar, this research has been cited \textbf{\textit{455}} %41+41+113+13+49+194+4
 times since 2003.