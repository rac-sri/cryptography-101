# Cryptography-101

The following document lists things you require to start your journey and understand different cryptography research areas. This repo aims to give a step by step guidance to exploring the world of cryptography.

### Some underlying concepts which are good to know
##### Prerequisites: None

##### Topics:
- One Time Pad
- PRP, PRFs, PRG
- Ciphers, Block Ciphers, MACs
- Encryption / Decryption

##### Resources:
- [Cryptography 1](https://www.coursera.org/learn/crypto/home/welcome) by Dan Boneh: Week 1 to Week 4. Assignments recommended.
- For more in-depth reading and problems check Dan's book [here](https://toc.cryptobook.us/)

---

### Fundamental Mathematics
##### Prerequisites: 
- Good foundation in mathematics.

##### Topics:
- Number Theory and Modular Arithmetic
- Finite Fields

##### Resources:
- [Number Theory](https://www.coursera.org/learn/crypto/home/welcome) Week 5, sections 3 and 4.
- [Fields](https://www.youtube.com/watch?v=MAhmV_omOwA&list=PLFX2cij7c2PynTNWDBzmzaD6ij170ILbQ&index=9&ab_channel=LambdaClass)
- [Montgomery arithmetic](https://www.youtube.com/watch?v=hUl8ZB6hpUM&t=142s&ab_channel=RISCZero)
- [Langrange Interpolation](https://www.geeksforgeeks.org/lagrange-interpolation-formula/)
- [Abstract Algebtra](https://www.youtube.com/watch?v=IP7nW_hKB7I&list=PLi01XoE8jYoi3SgnnGorR_XOW3IcK-TP6)

---

### Symmetric Cryptography
##### Prerequisites:
- Fundamental Mathematics
- Encryption/ Decryption

##### Topics:
- Key Exchange Protocols: Diffie Hellman

##### Resources
- [Public Key Encryption](https://www.coursera.org/learn/crypto/home/week/5) Week 5, section 1 and 2

---

### Asymmetric Cryptography
##### Prerequisites:
- Fundamental Mathematics
- Abstract Algebra

##### Topics:
- Public Key Cryptography
- Trapdoor Permutations, RSA
- ElGamal
- Digital Signatures
- Elliptic Curve Cryptography
- Pairings
- BLS Signatures

##### Resources:
- [Public Key, RSA, ElGamal](https://www.coursera.org/learn/crypto/home/week/6)
- [Digital Signatures explained](https://www.youtube.com/watch?v=s22eJ1eVLTU&ab_channel=Computerphile)
- [Digital Signatures](https://toc.cryptobook.us/)
- [ECC explained by Computerphile](https://www.youtube.com/watch?v=NF1pwjL9-DE&t=257s&ab_channel=Computerphile)
- [ECC by Dan Boneh](https://toc.cryptobook.us/)
- [Intuitive explanations of divisor and genus](https://math.stackexchange.com/questions/1609/intuitive-explanations-for-the-concepts-of-divisor-and-genus/1635#1635)
- [Pairings for Beginners](https://static1.squarespace.com/static/5fdbb09f31d71c1227082339/t/5ff394720493bd28278889c6/1609798774687/PairingsForBeginners.pdf)
- [Bilinear Pairings](https://twitter.com/privacy_prophet/status/1738503612094148718)
- [Bilinear Pairings in-depth](https://ntnuopen.ntnu.no/ntnu-xmlui/bitstream/handle/11250/2618796/no.ntnu%3Ainspera%3A2448650.pdf?sequence=1#:~:text=)
- [Bilinear Pairings by alinus](https://alinush.github.io/2022/12/31/pairings-or-bilinear-maps.html)
   
---

### Functional Encryption
##### Prerequisites: 
- Public Key cryptography

##### Topics:
- Attribute-Based Encryption
- Identity-Based Encryption
- Functional Encryption

##### Resources:
- [ABE by Allison Bishop](https://www.youtube.com/watch?v=89-1-JzNMpg&t=1513s&ab_channel=Bar-IlanUniversity-%D7%90%D7%95%D7%A0%D7%99%D7%91%D7%A8%D7%A1%D7%99%D7%98%D7%AA%D7%91%D7%A8-%D7%90%D7%99%D7%9C%D7%9F)
- [Functional Encryption by Allison Bishop](https://www.youtube.com/watch?v=PrsF_17TTrU&t=275s&ab_channel=Bar-IlanUniversity-%D7%90%D7%95%D7%A0%D7%99%D7%91%D7%A8%D7%A1%D7%99%D7%98%D7%AA%D7%91%D7%A8-%D7%90%D7%99%D7%9C%D7%9F)
- [Identity-Based encryptions by Dan Boneh](https://www.youtube.com/watch?v=Tt7cJnZDth0&ab_channel=Bar-IlanUniversity-%D7%90%D7%95%D7%A0%D7%99%D7%91%D7%A8%D7%A1%D7%99%D7%98%D7%AA%D7%91%D7%A8-%D7%90%D7%99%D7%9C%D7%9F)

---

### Zero Knowledge Proofs
##### Prequistics:
- Fields, Number Theory
- ECC
- Pairings

##### Topics Covered:
- Interactive Protocols
- Polynomial Commitment Schemes
- Snarks

##### Resources:
- [ZKP MOOC](https://www.youtube.com/watch?v=uchjTIlPzFo&list=PLS01nW3Rtgor_yJmQsGBZAg5XM4TSGpPs&ab_channel=Blockchain-Web3MOOCs)
- [Sum Check Protocol](https://rac-sri.medium.com/understanding-interactive-proof-systems-and-sum-check-protocol-part-1-6afd9edc67ec)
- [Programming Sum Check Protocol from scratch](https://rac-sri.medium.com/understanding-interactive-proof-systems-and-sum-check-protocol-part-2-a2eef4a1e061)
- Commitment Schemes:
   - [KZG](https://blog.rachitasrivastava.com/demystifying-kzg-poly-commit-scheme)
   - [Bulletproof](https://blog.rachitasrivastava.com/bulletproof-commitment-schemes-integrating-cryptography-and-mathematics)
   - [FRI](https://blog.rachitasrivastava.com/fri-polynomial-commitment-scheme)
- [Quadtratic Arithmetic](https://blog.rachitasrivastava.com/circuit-satisfiability-to-quadratic-arithmetic-program)
- [Groth16 article](https://blog.rachitasrivastava.com/groth-16-a-linear-pcp-based-snark)
- [Programming FRI from scratch](https://blog.lambdaclass.com/how-to-code-fri-from-scratch/)
- [Zk compilation from a16z](https://a16zcrypto.com/posts/article/zero-knowledge-canon/)
- [Matter Labs Awesome Zero-knowledge proofs](https://github.com/matter-labs/awesome-zero-knowledge-proofs?tab=readme-ov-file)


---

### Homomorphic Encryption

##### Topics Covered:
- Bfv scheme
- Bgv scheme
- Ckks scheme
- TFHE

##### Resources
- [Bfv scheme](https://www.inferati.com/blog/fhe-schemes-bfv)
- [Bgv scheme](https://www.inferati.com/blog/fhe-schemes-bgv)
- Ckks scheme
  - [Ckks explained](https://blog.openmined.org/ckks-explained-part-1-simple-encoding-and-decoding/)
  - [Ckks alternate read](https://hackmd.io/@rishotics/B1P69977R)
- [TFHE](https://www.zama.ai/post/tfhe-deep-dive-part-1)

--- 

### Programming ZKP

- [Circom](https://docs.circom.io/getting-started/installation/)
- [Gnark](https://docs.gnark.consensys.io/overview)
- [Arkworks](https://github.com/arkworks-rs/)
- [Zokrates](https://zokrates.github.io/)

--- 

For contributions, fork and create a pull request.
Feel free to connect with me on [Twitter](https://twitter.com/privacy_prophet) or [LinkedIn](https://www.linkedin.com/in/rachit-anand-srivastava-345307173/) for any suggestion/chat.
