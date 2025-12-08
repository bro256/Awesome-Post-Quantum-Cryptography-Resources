# 🔒 Awesome Post-Quantum Cryptography Resources
A curated collection of cutting-edge resources on **post-quantum cryptography (PQC)**.

![Last Commit](https://img.shields.io/github/last-commit/bro256/Awesome-Post-Quantum-Cryptography-Resources?label=Last%20Updated)

## 📖 Introduction  
Quantum computers will one day be powerful enough to break today’s widely used cryptographic systems, such as RSA and ECC.
To prepare for this shift, **post-quantum cryptography (PQC)** is being developed to ensure our digital world remains secure in the quantum era.

This repository brings together:
- 📜 **Standards & drafts** from NIST, IETF, and other bodies.
- 📚 **Handbooks, guides, and migration strategies** for organizations.
- 🛠 **Implementations, tools, and software** to experiment with PQC today.
- 🔬 **Research papers, publications, and events** driving the field forward.

Whether you’re a **developer**, **researcher**, or **security architect**, this list will help you stay up-to-date and navigate the transition toward **quantum-resistant cryptographic systems**.


## Table of Contents
1. [NIST Standards](#nist-standards)
2. [IETF](#ietf)
3. [Books and Handbooks](#books-and-handbooks)
4. [Migration Guides and Strategies](#migration-guides-and-strategies)
5. [Conferences and Events](#conferences-and-events)
6. [Research & Publications](#research-and-publications)
7. [Implementations](#implementations)
8. [Communities](#communities)
9. [Software and Tools](#software-and-tools)
10. [Talks & Videos](#talks-and-videos)
11. [Contributions](#contributions)


---
## NIST Standards
- [Post-Quantum Cryptography](https://www.nist.gov/pqcrypto)
#### Finalized PQC Standards
- [ML-KEM - FIPS 203](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.203.pdf) Module-Lattice-Based Key-Encapsulation Mechanism Standard ([CRYSTALS-Kyber](https://pq-crystals.org/kyber/) derived). Aug 13, 2024.
- [ML-DSA - FIPS 204](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.204.pdf) Module-Lattice-Based Digital Signature Standard ([CRYSTALS-Dilithium](https://pq-crystals.org/dilithium/) derived). Aug 13, 2024.
- [SLH-DSA - FIPS 205](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.205.pdf) Stateless Hash-Based Digital Signature Standard. ([SPHINCS+](https://sphincs.org/) derived). Aug 13, 2024.
#### Additional / Pre-existing Standards
- [FN - DSA](https://csrc.nist.gov/presentations/2024/navigating-floating-point-challenges-in-falcon) - [(Falcon)](https://falcon-sign.info)
- [HQC](https://www.nist.gov/news-events/news/2025/03/nist-selects-hqc-fifth-algorithm-post-quantum-encryption) - [(Hamming Quasi-Cyclic)](https://pqc-hqc.org/). Backup for ML-KEM. March 11, 2025
- [NIST SP 800-208](https://csrc.nist.gov/pubs/sp/800/208/final), Recommendation for Stateful Hash-Based Signature Schemes [LMS](https://www.rfc-editor.org/rfc/rfc8554.html), [XMSS](https://datatracker.ietf.org/doc/html/rfc8391)

## IETF
#### RFC:
- [RFC 9881. Internet X.509 Public Key Infrastructure - Algorithm Identifiers for the Module-Lattice-Based Digital Signature Algorithm (ML-DSA)](https://www.rfc-editor.org/rfc/rfc9881.html). Status: Proposed Standard. Oct, 2025.
- [RFC 9794. Terminology for Post-Quantum Traditional Hybrid Schemes](https://www.rfc-editor.org/rfc/rfc9794.html). Status: Informational. Jun 2025.
- [RFC 8554. LMS. Leighton-Micali Hash-Based Signatures](https://www.rfc-editor.org/rfc/rfc8554.html). Status: Informational. Apr 2019
#### Drafts:
- [Composite ML-DSA for use in X.509 Public Key Infrastructure](https://datatracker.ietf.org/doc/draft-ietf-lamps-pq-composite-sigs/)
- [Post-quantum hybrid ECDHE-MLKEM Key Agreement for TLSv1.3](https://datatracker.ietf.org/doc/draft-ietf-tls-ecdhe-mlkem/)
- [TLS Key Share Prediction](https://datatracker.ietf.org/doc/draft-ietf-tls-key-share-prediction)
- [Hybrid key exchange in TLS 1.3](https://datatracker.ietf.org/doc/html/draft-ietf-tls-hybrid-design)

## Books and Handbooks
- [The PQC Migration Handbook](https://english.aivd.nl/publications/publications/2024/12/3/the-pqc-migration-handbook). AIVD, CWI, TNO. Dec, 2024.

## Migration Guides and Strategies
- [Guidelines for Cryptography](https://www.cyber.gov.au/resources-business-and-government/essential-cyber-security/ism/cyber-security-guidelines/guidelines-cryptography). Australian Signals Directorate. 12 Dec, 2024.
- [Recommendation on a Coordinated Implementation Roadmap for the transition to Post-Quantum Cryptography](https://digital-strategy.ec.europa.eu/en/library/recommendation-coordinated-implementation-roadmap-transition-post-quantum-cryptography). European Commission. Apr 11, 2024.
- [Google's Threat model for Post-Quantum Cryptography](https://bughunters.google.com/blog/5108747984306176/google-s-threat-model-for-post-quantum-cryptography). Google. Mar 11, 2024.
- [PQC - Guidelines for Telco Use Cases - Executive Summary](https://www.gsma.com/newsroom/wp-content/uploads//PQC-Guidelines-for-Telco-Use-Cases-Executive-Summary.pdf). GSMA. Feb, 2024.
- [Post Quantum Cryptography - Guidelines for Telco Use Cases](https://www.gsma.com/newsroom/wp-content/uploads//PQ.03-Post-Quantum-Cryptography-Guidelines-for-Telecom-Use-v1.0.pdf). GSMA. Feb 22, 2024.
- [Next steps in preparing for post-quantum cryptography](https://www.ncsc.gov.uk/whitepaper/next-steps-preparing-for-post-quantum-cryptography): Guidance to help organisations and CNI providers think about how to best prepare for the migration to post-quantum cryptography (PQC). National Cyber Security Centre (UK). Nov 3, 2023.
- [Summary of NATO’s Quantum Technologies Strategy](https://www.nato.int/cps/en/natohq/official_texts_221777.htm). NATO. Jan 17, 2024.

## Conferences and Events
- [Post-Quantum Cryptography Conference. October 28 - 30, 2025 - Kuala Lumpur, Malaysia](https://pkic.org/events/2025/pqc-conference-kuala-lumpur-my/). PKI Consortium. Oct, 2025.
- [OpenSSL Conference. Prague 2025. October 7-9, 2025](https://www.youtube.com/@OpenSSLConference). OpenSSL. Oct, 2025.
- [Post-Quantum Cryptography Conference. January 15 and 16, 2025 - Austin, Texas, US](https://pkic.org/events/2025/pqc-conference-austin-us/). PKI Consortium. Jan, 2025.

## Research and Publications
- [Performance and Storage Analysis of CRYSTALS Kyber as a Post Quantum Replacement for RSA and ECC](https://arxiv.org/abs/2508.01694v1). Cornell University. Aug 30, 2025.
- [Quantum-safe security: Progress towards next-generation cryptography](https://www.microsoft.com/en-us/security/blog/2025/08/20/quantum-safe-security-progress-towards-next-generation-cryptography/). Microsoft. Aug 20, 2025.
- [Ballot SMC013: Enable PQC Algorithms for S/MIME](https://cabforum.org/2025/07/02/ballot-smc-013/). CA/Browser Forum. Jul 2, 2025.
- [A Coordinated Implementation Roadmap for the Transition to Post-Quantum Cryptography](https://digital-strategy.ec.europa.eu/en/library/coordinated-implementation-roadmap-transition-post-quantum-cryptography). European Commission. June 23, 2025.
- [Post-Quantum Cryptography Migration Roadmap](https://pqcc.org/wp-content/uploads/2025/05/PQC-Migration-Roadmap-PQCC-2.pdf). Post-Quantum Cryptography Coalition. May, 2025.
- [Post-Quantum Cryptography Comes to Windows Insiders and Linux](https://techcommunity.microsoft.com/blog/microsoft-security-blog/post-quantum-cryptography-comes-to-windows-insiders-and-linux/4413803). Microsoft. May 19, 2025.
- [Prepping for post-quantum: a beginner’s guide to lattice cryptography](https://blog.cloudflare.com/lattice-crypto-primer/). Cloudflare. Mar 21, 2025.
- [Timelines for migration to post-quantum cryptography](https://www.ncsc.gov.uk/guidance/pqc-migration-timelines). National Cyber Security Centre (UK). Mar 20, 2025.
- [Quantum Safe Financial Forum - A call to action](https://www.europol.europa.eu/cms/sites/default/files/documents/Quantum-safe-financial-forum-2025.pdf). Europol. Feb 7, 2025.
- [Post Quantum Computing Security](https://www.5gamericas.org/wp-content/uploads/2025/02/WP_PQCS-.pdf). 5G Americas. Feb, 2025.
- [Guidance on securely configuring network protocols](https://www.cyber.gc.ca/en/guidance/guidance-securely-configuring-network-protocols-itsp40062). Canadian Centre for Cyber Security. Jan, 2025.
- [Quantum Threat Timeline Report 2024](https://globalriskinstitute.org/publication/2024-quantum-threat-timeline-report/). Global Risk Institute. Dec 6, 2024.
- [Securing Tomorrow, Today: Transitioning to Post-Quantum Cryptography](https://www.bsi.bund.de/SharedDocs/Downloads/EN/BSI/Crypto/PQC-joint-statement.pdf?__blob=publicationFile&v=3). BSI. Nov 27, 2024.
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

## Implementations
- [Post-Quantum Cryptography APIs Now Generally Available on Microsoft Platforms](https://techcommunity.microsoft.com/blog/microsoft-security-blog/post-quantum-cryptography-apis-now-generally-available-on-microsoft-platforms/4469093). Microsoft. Nov 18, 2025
- [Fortinet adds quantum-safe encryption to FortiOS 7.6 update](https://www.fortinet.com/corporate/about-us/newsroom/press-releases/2025/fortinet-advances-quantum-safe-security-to-guard-against-emerging-quantum-threats). Fortinet. Jul 22, 2025.
- [Post-Quantum Cryptography in Kubernetes](https://kubernetes.io/blog/2025/07/18/pqc-in-k8s/). Kubernetes. Jul 18, 2025.
- [Prepare your network for quantum-secure encryption in TLS](https://support.apple.com/en-us/122756). Apple. June 09, 2025.
- [Introducing PQC Algorithms in SymCrypt](https://techcommunity.microsoft.com/t5/security-compliance-and-identity/microsoft-s-quantum-resistant-cryptography-is-here/ba-p/4238780). Microsoft. Sep 09, 2024. Updated Dec 18, 2024.
- [Customer compliance and security during the post-quantum cryptographic migration](https://aws.amazon.com/blogs/security/customer-compliance-and-security-during-the-post-quantum-cryptographic-migration/). AWS. Oct 03, 2024.
- [NordVPN launches first app with post-quantum encryption support](https://nordvpn.com/blog/nordvpn-linux-post-quantum-encryption-support/). NordVPN. Sep 30, 2024.
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

## Talks and Videos
- [OpenSSL Conference](https://www.youtube.com/@OpenSSLConference)
- [PKI Consortium YouTube Channel ](https://youtube.com/@PKIConsortium/)
- 
 
## Contributions

We welcome and encourage contributions!
This project thrives on community input — from researchers, engineers, and enthusiasts alike.

### How to Contribute
1. **Check for duplicates** – ensure the resource isn’t already listed.
2. **Use credible sources** – academic papers, official standards, recognized organizations, or trusted industry blogs.
3. **Provide full references** – include title, author/organization, date (if available), and a working link.
4. **Keep it relevant** – focus on post-quantum cryptography and quantum-safe security.

### Contribution Examples
- Add new **publications, events, or standards**.
- Suggest **tools, libraries, or implementations**.
- Report **outdated or broken links**.
- Improve **organization or categorization** of resources.

### How to Submit
- **Pull Requests (preferred):** Add your resource directly to the right section.
- **Issues:** If you’re unsure where something fits, open an issue with details.

📌 Please use this format when adding resources:
- [Title](URL) — Short description. Organization/Author. Month Day, Year.

