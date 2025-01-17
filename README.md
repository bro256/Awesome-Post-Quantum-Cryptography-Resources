# Awesome-Post-Quantum-Cryptography-Resources
A curated list of up-to-date resources on post-quantum cryptography.


## Introduction
Post-quantum cryptography (PQC) is a critical area of research and development to secure our digital world against future quantum computing threats. This repository is a curated collection of the latest standards, publications, and resources to help developers, researchers, and organizations transition to quantum-resistant cryptographic systems.


## Table of Contents
1. [Standards](#standards)
2. [Publications](#publications)
3. [Guides](#guides)
4. [Implementations](#implementations)
5. [IETF](#ietf)


---

## Standards
- [FIPS 203](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.203.pdf) ML-KEM (Module-Lattice-Based Key-Encapsulation Mechanism Standard). Derived from CRYSTALS-Kyber. Aug 13, 2024.
- [FIPS 204](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.204.pdf) ML-DSA (Module-Lattice-Based Digital Signature Standard). Derived from CRYSTALS-Dilithium. Aug 13, 2024.
- [FIPS 205](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.205.pdf) SLH-DSA (Stateless Hash-Based Digital Signature Standard). Derived from SPHINCS+. Aug 13, 2024.

## Publications
- [Securing Tomorrow, Today: Transitioning to Post-Quantum Cryptography](https://www.bsi.bund.de/SharedDocs/Downloads/EN/BSI/Crypto/PQC-joint-statement.pdf?__blob=publicationFile&v=3). BSI. Nov 27. 2024.
- [NIST IR 8547 (Initial Public Draft)](https://csrc.nist.gov/pubs/ir/8547/ipd): Transition to Post-Quantum Cryptography Standards. NIST. Nov 24, 2024.
- [A look at the latest post-quantum signature standardization candidates](https://blog.cloudflare.com/another-look-at-pq-signatures/). Cloudflare. Nov 7, 2024.
- [Begin Transitioning to Post-Quantum Cryptography Now](https://www.gartner.com/en/articles/post-quantum-cryptography). Gartner. Sep 30, 2024.
- [A new path for Kyber on the web](https://security.googleblog.com/2024/09/a-new-path-for-kyber-on-web.html). Google. Sep 13, 2024.
- [Developing with quantum-safe OpenSSL](https://developer.ibm.com/tutorials/awb-quantum-safe-openssl/). IBM. Aug 21, 2024.
- [NIST SPECIAL PUBLICATION 1800-38B](https://www.nccoe.nist.gov/sites/default/files/2023-12/pqc-migration-nist-sp-1800-38b-preliminary-draft.pdf): Migration to Post-Quantum Cryptography Quantum Readiness: Cryptographic Discovery. NIST. Dec, 2023.
- [NIST SPECIAL PUBLICATION 1800-38C](https://www.nccoe.nist.gov/sites/default/files/2023-12/pqc-migration-nist-sp-1800-38c-preliminary-draft.pdf): Migration t:o Post-Quantum Cryptography Quantum Readiness: Testing Draft Standards. NIST. Dec, 2023.
- [Follow up position paper on Post-Quantum Cryptography](https://cyber.gouv.fr/en/publications/follow-position-paper-post-quantum-cryptography). ANSSI. Oct 11, 2023.
- [NIST SPECIAL PUBLICATION 1800-38A](https://www.nccoe.nist.gov/sites/default/files/2023-04/pqc-migration-nist-sp-1800-38a-preliminary-draft.pdf). Migration to Post-Quantum Cryptography: Preparation for Considering the Implementation and Adoption of Quantum Safe Cryptography. NIST. May 2, 2023.
- [The Cornerstone of Cybersecurity – Cryptographic Standards and a 50-Year Evolution](https://www.nist.gov/blogs/cybersecurity-insights/cornerstone-cybersecurity-cryptographic-standards-and-50-year-evolution). NIST. May 26, 2022.
- [Quantum-safe cryptography – fundamentals, current developments and recommendations](https://www.bsi.bund.de/SharedDocs/Downloads/EN/BSI/Publications/Brochure/quantum-safe-cryptography.pdf?__blob=publicationFile&v=6). BSI. May 18, 2022.
- [ANSSI views on the Post-Quantum Cryptography transition](https://cyber.gouv.fr/en/publications/anssi-views-post-quantum-cryptography-transition). ANSSI. Jan 4, 2022.

## Guides
- [Guidelines for Cryptography](https://www.cyber.gov.au/resources-business-and-government/essential-cyber-security/ism/cyber-security-guidelines/guidelines-cryptography). Australian Signals Directorate. 12 Dec, 2024
- [Recommendation on a Coordinated Implementation Roadmap for the transition to Post-Quantum Cryptography](https://digital-strategy.ec.europa.eu/en/library/recommendation-coordinated-implementation-roadmap-transition-post-quantum-cryptography). European Commission. Apr 11, 2024.
- [Google's Threat model for Post-Quantum Cryptography](https://bughunters.google.com/blog/5108747984306176/google-s-threat-model-for-post-quantum-cryptography). Google. Mar 11, 2024.
- [PQC - Guidelines for Telco Use Cases - Executive Summary](https://www.gsma.com/newsroom/wp-content/uploads//PQC-Guidelines-for-Telco-Use-Cases-Executive-Summary.pdf). GSMA. Feb, 2024.
- GSMA. [Post Quantum Cryptography - Guidelines for Telco Use Cases](https://www.gsma.com/newsroom/wp-content/uploads//PQ.03-Post-Quantum-Cryptography-Guidelines-for-Telecom-Use-v1.0.pdf). Feb 22, 2024.
- [Next steps in preparing for post-quantum cryptography](https://www.ncsc.gov.uk/whitepaper/next-steps-preparing-for-post-quantum-cryptography): Guidance to help organisations and CNI providers think about how to best prepare for the migration to post-quantum cryptography (PQC). National Cyber Security Centre (UK). Nov 3, 2023.
- [Summary of NATO’s Quantum Technologies Strategy](https://www.nato.int/cps/en/natohq/official_texts_221777.htm). NATO. Jan 17, 2024.

## Implementations
- [Customer compliance and security during the post-quantum cryptographic migration](https://aws.amazon.com/blogs/security/customer-compliance-and-security-during-the-post-quantum-cryptographic-migration/). AWS. Oct 03, 2024.
- [NordVPN launches first app with post-quantum encryption support](https://nordvpn.com/blog/nordvpn-linux-post-quantum-encryption-support/). NordVPN. Sep 30, 2024.
- [Introducing PQC Algorithms in SymCrypt](https://techcommunity.microsoft.com/t5/security-compliance-and-identity/microsoft-s-quantum-resistant-cryptography-is-here/ba-p/4238780). Microsoft. Sep 09, 2024.
- [Advancing Our Amazing Bet on Asymmetric Cryptography](https://blog.chromium.org/2024/05/advancing-our-amazing-bet-on-asymmetric.html). Google. May 23, 2024.
- [iMessage with PQ3: The new state of the art in quantum-secure messaging at scale](https://security.apple.com/blog/imessage-pq3/). Apple. Feb 21, 2024.
- [The PQXDH Key Agreement Protocol](https://signal.org/docs/specifications/pqxdh/pqxdh.pdf). Signal. Jan 23, 2024.
- [Cloudflare now uses post-quantum cryptography to talk to your origin server](https://blog.cloudflare.com/post-quantum-to-origins). CloudFlare. Sep 29, 2023.
- [Quantum Resistance and the Signal Protocol](https://signal.org/blog/pqxdh/). Signal. Sep 19, 2023.
- [Protecting Chrome Traffic with Hybrid Kyber KEM](https://blog.chromium.org/2023/08/protecting-chrome-traffic-with-hybrid.html). Google. Aug 10, 2023.

## Communities
- [PKI Consortium](https://pkic.org/)

## Software and Tools
 - [Open Quantum Safe](https://openquantumsafe.org/)

## IETF
- [TLS Key Share Prediction](https://datatracker.ietf.org/doc/draft-ietf-tls-key-share-prediction)
- [Hybrid key exchange in TLS 1.3](https://datatracker.ietf.org/doc/html/draft-ietf-tls-hybrid-design)

## eBooks and Handbooks
- [The PQC Migration Handbook](https://publications.tno.nl/publication/34641918/oicFLj/attema-2023-pqc.pdf). TNO. Dec, 2023.
 

## Contributions  
Contributions are welcome! If you know of any trusted and reliable resources, publications, or updates, feel free to submit a pull request or open an issue.  

Please ensure that all contributions:  
1. **Are from credible sources** such as academic journals, recognized organizations, or official standards bodies.  
2. **Include proper references** (e.g., links to original publications or announcements).  
3. Are relevant to the field of post-quantum cryptography.  


