---
title: "Loquat: A SNARK-Friendly Post-Quantum Signature based on the Legendre PRF with Applications in Ring and Aggregate Signatures"
collection: publications
category: conferences
permalink: /publication/Loquat
year: 2024
venue: 'Annual International Cryptology Conference (Crypto 2024)'
Page: 3 - 38
Publisher: Springer Nature Switzerland
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-68376-3_1'
Authors: 'Xinyu Zhang, Ron Steinfeld, Muhammed Esgin, Joseph Liu, Dongxi Liu, and Sushmita Ruj'
---

We design and implement a novel post-quantum signature scheme based on the Legendre PRF, named Loquat. Prior to this work, efficient approaches for constructing post-quantum signatures with comparable security assumptions mainly used the MPC-in-the-head paradigm or hash trees. Our method departs from these paradigms and, notably, is SNARK-friendly, a feature not commonly found in earlier designs.
Loquat requires significantly fewer computational operations for verification than other symmetric-key-based post-quantum signature schemes that support stateless many-time signing. Notably, the performance of Loquat remains practical even when employing algebraic hash functions. Our Python-based implementations of Loquat demonstrate a signature size of 46KB, with a signing time of 5.04 seconds and a verification time of merely 0.21 seconds. Instantiating the random oracle with an algebraic hash function results in the R1CS constraints for signature verification being about 148K, 7 to 175 times smaller than those required for state-of-the-art MPC-in-the-head-based signatures and 3 to 9 times less than those for SPHINCS+ [Bernstein et al. CCS’19]. We explore two applications of Loquat. First, we incorporate it into the ID-based ring signature scheme [Buser et al. ACNS’22], achieving a significant reduction in signature size from 1.9 MB to 0.9 MB with stateless signing and practical master key generation. Our second application presents a SNARK-based aggregate signature scheme. We use the implementations of Aurora [Ben-Sasson et al. EC’19] and Fractal [Chiesa et al. EC’20] to benchmark our aggregate signature’s performance. Our findings show that aggregating 32 Loquat signatures using Aurora results in a proving time of about 7 minutes, a verification time of 66 seconds, and an aggregate signature size of 197 KB. Furthermore, by leveraging the recursive proof composition feature of Fractal, we achieve an aggregate signature with a constant size of 145 KB, illustrating Loquat’s potential for scalability in cryptographic applications.
