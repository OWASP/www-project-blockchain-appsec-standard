# OWASP Blockchain AppSec Standard

<p align="center">
  <img src="assets/images/owasp-blockchain-appsec-standard.PNG" alt="OWASP Blockchain AppSec Standard" width="600">
</p>

The **OWASP Blockchain AppSec Standard** is a community-driven application security (AppSec) and information security (infosec) knowledge base for understanding, assessing, and improving the security of blockchain-based applications and Web3 systems. It brings together security concepts, attack vectors, defensive practices, and practical resources to help teams make informed security decisions throughout the software development lifecycle (SDLC).

The project is part of the [OWASP Foundation](https://owasp.org/) and welcomes contributions from developers, architects, security practitioners, researchers, and other stakeholders working with blockchain technology.

## Purpose

This repository documents and communicates what good application security (AppSec) looks like in blockchain and Web3 environments. It aims to:

- Explain blockchain and Web3 security concepts in clear, consistent terminology.
- Describe relevant threats, attack vectors, weaknesses, and defensive mechanisms.
- Organize security guidance and references so practitioners can apply them during the design, development, deployment, and operation of blockchain-based solutions.
- Help developers and security professionals identify security considerations across the software development lifecycle.
- Provide a collaborative, maintainable resource that evolves with the technology and the security community.

The project is an educational and reference resource. It is not a certification, a guarantee of security, or a substitute for a product-specific security assessment.

## Project scope

The standard focuses on **application and system security for blockchain and Web3 solutions**. Its coverage is intended to include security considerations associated with:

- **Blockchain architecture and networks:** distributed ledger technologies, nodes, network components, consensus mechanisms, trust assumptions, and permissions that underpin blockchain systems.
- **Application architecture and development:** Web3 decentralized applications (dApps), APIs, integrations, client applications, frameworks, libraries, and dependencies, with AppSec practices applied to their design and implementation.
- **Identity, wallets, and cryptographic assets:** public- and private-key management, wallet security, authentication, authorization, and protection of digital assets.
- **Secure software development:** security requirements, architecture and design review, threat modeling, secure implementation, configuration, and change management across the SDLC.
- **Security verification and testing:** code and configuration review, vulnerability assessment, penetration testing, and application and API security testing.
- **Deployment and operations:** infrastructure and access controls, logging and monitoring, vulnerability and patch management, incident response, and forensic readiness.
- **Governance and risk:** information security policies, governance, operational processes, and lifecycle practices that support the secure delivery and maintenance of blockchain solutions.

These areas provide a framework for organizing community knowledge. Specific guides and recommendations may be expanded, refined, or added as the project develops.

### Out of scope

Detailed smart contract security verification is addressed by the separate [OWASP Smart Contract Security Verification Standard (SCVS)](https://owasp.org/www-project-smart-contract-security-verification-standard/). This project may explain smart contracts and reference smart contract risks where they are relevant to the wider application or system context, but it does not seek to duplicate SCVS.

## Intended audience

The project supports people who design, build, secure, assess, operate, contribute to, or govern blockchain-based applications and infrastructure.

### Primary audience: developers and technical practitioners

- Blockchain and Web3 developers.
- Application, platform, and infrastructure architects.
- Security engineers, AppSec practitioners, and penetration testers.
- Engineers responsible for wallets, APIs, integrations, nodes, and decentralized applications.

### Secondary audience: security leadership and governance

- Information security professionals and security leaders.
- Risk, compliance, and governance practitioners.
- Product owners and technical decision-makers responsible for blockchain solutions.
- Researchers, educators, and organizations developing security practices.

### Contributors and community users

Contributors may include developers, security researchers, reviewers, technical writers, and community members. You do not need to be an expert in every area to help improve the project: documentation improvements, issue reports, references, reviews, and new topic proposals are all valuable.

## Project resources

- [OWASP project page](https://owasp.org/projects/blockchain-appsec-standard)
- [Project website and knowledge base](https://owasp.github.io/www-project-blockchain-appsec-standard/)
- [Guides directory](guides/)
- [Contributing guidelines](CONTRIBUTING.md)
- [OWASP Smart Contract Security Verification Standard](https://owasp.org/www-project-smart-contract-security-verification-standard/)

## Contributing

Community participation helps keep the standard useful, accurate, and relevant. To contribute:

1. Review the project scope and existing [guides](guides/) to understand current coverage.
2. Identify an improvement, correction, missing security topic, or useful reference.
3. Open an issue to discuss substantial changes or a new guide before beginning work.
4. Submit a pull request with focused, clearly documented changes.
5. Explain the rationale and supporting references, and identify any affected guides or terminology.

Please follow the [Contributing Guidelines](CONTRIBUTING.md) and the [OWASP Code of Conduct](https://owasp.org/www-policy/operational/code-of-conduct).

## License

This repository's content is licensed under the [Apache License, Version 2.0](LICENSE.md). You may use, reproduce, and distribute the licensed materials in accordance with the terms and conditions in that file. Please review [LICENSE.md](LICENSE.md) for the complete license text, permissions, and conditions.
