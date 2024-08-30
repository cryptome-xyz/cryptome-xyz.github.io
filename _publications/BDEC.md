--- 
title: "DualRing-PRF: Post-Quantum (Linkable) Ring Signatures from Legendre and Power Residue PRFs" 
collection: publications category: conference permalink: /publication/DualRing_PRF 
year: 2024 
venue: 'The 29th Australasian Conference on Information Security and Privacy' Page: 124 -- 143 
publisher: Springer Nature Singapore 
paperurl: 'https://link.springer.com/chapter/10.1007/978-981-97-5028-3_7' 
authors: 'Xinyu Zhang, Ron Steinfeld, Joseph Liu, Muhammed Esgin, Dongxi Liu, and Sushmita Ruj' 
---

Digital credentials can streamline the verification process, reduce fraud, and enhance the portability and accessibility of academic records, and thus digital credentials become increasingly essential for verifying academic achievements and qualifications in a rapidly digitizing world. However, current research on digital credentials in the education scenario falls into two categories: 1) blockchain-verifiable credentials, which either rely on blockchain security or classical cryptographic problems and are not quantum-safe; and 2) post-quantum anonymous credentials, primarily lattice-based, facing challenges in achieving conditional linkability and efficient revocation. In this paper, we propose a generic framework for constructing an anonymous credential system named Blockchain-based Digital Education Credential (BDEC). Our framework requires only a digital signature scheme and a zkSNARK. We formally prove the unforgeability, anonymity, and unlinkability of the proposed framework and show that it additionally supports conditional linkability and revocability. By instantiating the framework with the post-quantum signature Loquat [Crypto’24] and zkSNARK Aurora [Eurocrypt’19], we construct a post-quantum anonymous credential system whose security relies on collision-resistant hash functions and the Legendre PRF. Furthermore, our resulting system offers significant improvements in its concrete performance over the lattice-based system [Crypto’23]
