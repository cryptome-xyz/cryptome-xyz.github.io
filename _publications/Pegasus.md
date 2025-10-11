---
title: "Pegasus and PegaRing: Efficient (Ring) Signatures from Sigma-Protocols for Power Residue PRFs with (Q)ROM Security"
collection: publications
category: eprint
permalink: /publication/Pegasus
date: 2025-10-08
paperurl: 'https://eprint.iacr.org/2025/1841.pdf'
---
Keywords: Legendre and Power Residue PRFs, Sigma Protocol, Post-Quantum, Signature, Ring Signature, QROM

In this work, we present a novel commit-and-open protocol based on the Legendre and power residue PRFs. Our construction leverages the oblivious linear evaluation (OLE) correlations inherent in PRF evaluations and requires only black-box access to a tree-PRG-based vector commitment. By applying the standard Fiat-Shamir transform, we obtain a post-quantum signature scheme, Pegasus, which achieves short signature sizes (6025 to 7878 bytes) with efficient signing (3.910 to 19.438 ms) and verification times (3.942 to 18.999 ms). Furthermore, by pre-computing the commitment phase, the online response time can be reduced to as little as 0.047 to 0.721 ms. We prove the security of Pegasus in both the classical random oracle model (ROM) and the quantum random oracle model (QROM), filling a gap left by prior PRF-based signature schemes. 

We further develop a ring signature scheme, PegaRing, that preserves the three-move commit-and-open structure of Pegasus. Compared to previous PRF-based ring signature called DualRing-PRF (ACISP 2024), PegaRing reduces the constant communication overhead by more than half and achieves significantly faster signing and verification. For a ring size of 1024, PegaRing yields signatures of 29 to 32 KB, with signing times of 8 to 44 ms, and verification times of 6 to 31 ms, depending on the parameters. Finally, we prove the security of PegaRing in both the ROM and the QROM, which is, to the best of our knowledge, the first symmetric-key primitives-based ring signature with practical performances and provable QROM security.
