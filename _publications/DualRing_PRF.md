---
title: "DualRing-PRF: Post-Quantum (Linkable) Ring Signatures from Legendre and Power Residue PRFs"
collection: publications
category: conference
permalink: /publication/DualRing_PRF
year: 2024
venue: 'The 29th Australasian Conference on Information Security and Privacy (ACISP 2024)'
Page: 124 -- 143
Publisher: Springer Nature Singapore
paperurl: 'https://link.springer.com/chapter/10.1007/978-981-97-5028-3_7'
Authors: 'Xinyu Zhang, Ron Steinfeld, Joseph Liu, Muhammed Esgin, Dongxi Liu, and Sushmita Ruj'
---

Ring signatures are one of the crucial cryptographic primitives used in the design of privacy-preserving systems. Such a signature scheme allows a signer to anonymously sign a message on behalf of a spontaneously formed group. It not only ensures the authenticity of the message but also conceals the true signer within the group. An important extension of ring signatures is \textit{linkable} ring signatures, which prevent a signer from signing twice without being detected (under some constraints). Linkable ring signatures offer advantages in applications where full anonymity might jeopardise the intended purpose, such as privacy-oriented cryptocurrencies like Monero.

In this work, we introduce post-quantum ring signature (DualRing-PRF) and linkable ring signature (DualRingL-PRF) schemes whose security solely rely on symmetric-key primitives (namely, Legendre PRF and power residue PRF). Our construction of the ring signature departs from previous approaches with similar security assumptions, offering the most competitive signature sizes for small and medium-sized rings. In particular, for a ring size of 16, DualRing-PRF has a communication overhead 1.4 times smaller than the state-of-the-art scheme proposed by Goel et al. [PETS'21]. Furthermore, we demonstrate the extension of DualRing-PRF to incorporate linkability and non-slanderability. Compared to the existing \emph{one-time} traceable ring signature (a variant of linkable ring signature) by Scafuro and Zhang [ESORICS'21], our construction supports many-time signing and achieves significantly smaller signature sizes when ring size exceeds $16$. This advantage becomes more pronounced as the ring size increases.
