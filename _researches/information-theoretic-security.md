---
title: Classical and Quantum Information Theoretic Security
type: topic
layout: research
---

Information theoretic security is a new emerging research area of information theory. This area contains two important applied topics, one is the security analysis of the quantum key distribution, and the other is the security analysis of physical layer security, which contains the information theoretic security of wireless communication. To realize the security, we usually apply a hash function. Hence, we do not have the difficulty caused by decoding, which is the main difference from the error correcting code. Dr. Hayashi firstly pointed out that the useful relation between the wire-tap channel and the channel resolvability. Then, he derived an exponential decreasing rate of leaked information in the wire-tap channel model. Usually, we employ an auxiliary random variable as a scramble parameter for the code of wire-tap channel. All existing studies assume its perfect uniformity nevertheless it is quite difficult to guarantee it. To guarantee the security even with non-uniform auxiliary random variable, he invented a new security formula for wire-tap channel code based on the Renyi entropy of the non-uniform auxiliary random variable. Then, I succeeded in evaluating the security with such an imperfect case. Also, I proposed a practical code construction by using a linear code. These results removed several obstacles for real application of wire-tap channel model.

> **M. Hayashi**, “General non-asymptotic and asymptotic formulas in channel resolvability and identification capacity and its application to wire-tap channel," *IEEE Transactions on Information Theory*, Vol. 52, No. 4, 1562-1575 (2006).

This paper pointed out the clear connection between the wire-tap channel coding and the channel resolvability. Using this connection, this paper derived an explicit exponent for leaked information by using Arimoto's exponents. Also, combining the information spectrum approach, this paper revealed the capacity formula of general sequence of degraded wire-tap channels. Since this connection is a very powerful tool for ire-tap channel, many papers for wire-tap channel followed this idea to construct codes for wire-tap channel. Further, this paper proved the conjecture for resolvability capacities for general sequence of channel, which had been an open problem proposed by Han-Verdu in 1993 (13 years).

> **M. Hayashi**, “Exponential decreasing rate of leaked information in universal random privacy amplification,” *IEEE Transactions on Information Theory*, Vol. 57, No. 6, 3989–4001 (2011).

This paper addresses security analysis when hash functions are applied. It applies hash function to wiretap channel, and constructs a practical code with small encoding and decoding time in finite-length setting



------



I also discussed the secure key generation from random number partially leaked to the eavesdropper. In this model, he derived the tight exponential decreasing rate of leaked information under the application of a universal2 hash function. This bound also works for the finite-length bound for leaked information. To realize this protocol, it is enough to consider the calculation complexity of universal2 hash function. I also showed that universal2 hash function can be implemented by employing the Toeplitz matrix, whose multiplication has less calculation complexity. Therefore, his evaluation can be directly applied to the real physical layer security system. I also extended these result to the quantum setting by resolving the difficulties caused by the non-commutativity. Based on these results, I also established a security formula to guarantee the security of real quantum key distribution system that contains imperfectness in the photon source as well as in the optical communication channel. 

> **M. Hayashi**, “Practical Evaluation of Security for Quantum Key Distribution," *Physical Review A*, Vol.74, 022307 (2006).

This paper discussed the second-order analysis for quantum key distribution with single-photon setting.

> **M. Hayashi**, “Upper bounds of eavesdropper’s performances in finite-length code with the decoy method," *Physical Review A*, Vol.76, 012329 (2007); *Physical Review A*, Vol.79, 019901(E) (2009).

This paper derives the relation between phase error probability and leaked information and provides a formula for leaked information with imperfect photon source in quantum key distribution in finite-length setting.

> **M. Hayashi**, “Large deviation analysis for quantum security via smoothing of Renyi entropy of order 2,” *IEEE Transactions on Information Theory*, Vol. 60, No. 10, 6702 – 6732 (2014).

This paper discusses the secure-random number generation in the quantum setting.