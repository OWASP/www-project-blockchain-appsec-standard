# OWASP Blockchain AppSec Standard

<p align="center">
  <img src="assets/images/owasp-blockchain-appsec-standard.PNG" alt="OWASP Blockchain AppSec Standard" width="600">
</p>

The **OWASP Blockchain AppSec Standard** is a community-driven knowledge base for understanding, assessing, and improving the security of blockchain-based applications and Web3 systems. It brings together security concepts, attack vectors, defensive practices, and practical resources to help teams make informed security decisions throughout the software development lifecycle (SDLC).

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

- **Blockchain architecture and networks:** distributed ledgers, nodes, network components, consensus mechanisms, trust assumptions, and permissions.
- **Application architecture and development:** decentralized applications (dApps), APIs, integrations, client applications, frameworks, libraries, and dependencies.
- **Identity, wallets, and cryptographic assets:** public- and private-key management, wallet security, authentication, authorization, and protection of digital assets.
- **Secure software development:** security requirements, architecture and design review, threat modeling, secure implementation, configuration, and change management.
- **Security verification and testing:** code and configuration review, vulnerability assessment, penetration testing, and application and API security testing.
- **Deployment and operations:** infrastructure and access controls, logging and monitoring, vulnerability and patch management, incident response, and forensic readiness.
- **Governance and risk:** security policies, operational processes, and lifecycle practices that support the secure delivery and maintenance of blockchain solutions.

These areas provide a framework for organizing community knowledge. Specific guides and recommendations may be expanded, refined, or added as the project develops.

### Out of scope

Detailed smart contract security verification is addressed by the separate [OWASP Smart Contract Security Verification Standard (SCVS)](https://owasp.org/www-project-smart-contract-security-verification-standard/). This project may explain smart contracts and reference smart contract risks where they are relevant to the wider application or system context, but it does not seek to duplicate SCVS.

## Terminology and project topics

The repository's GitHub topics describe the project's subject areas and help people discover related OWASP resources. The README uses those terms in context:

| GitHub topic | How it relates to this project |
| --- | --- |
| `appsec` | Application security practices for blockchain-based applications, dApps, APIs, and integrations. |
| `blockchain` | Distributed ledger technologies, networks, architecture, consensus, and associated components. |
| `infosec` | Information security principles, threats, risk management, and protective controls. |
| `owasp` | Community-developed security guidance aligned with the OWASP mission and resources. |
| `policy` | Security policies, governance, permissions, and operational processes relevant to blockchain solutions. |
| `sdlc` | Security activities across requirements, design, implementation, verification, deployment, and maintenance. |
| `security` | The broader set of technical and organizational measures used to protect blockchain applications and supporting systems. |
| `web3` | Decentralized applications, digital assets, wallets, and services built using blockchain technologies. |

### Key concepts

- **Blockchain:** A distributed ledger technology in which transactions are recorded and validated according to the rules and consensus mechanism of a network.
- **Web3:** An ecosystem of applications and services that use decentralized technologies, including blockchain, to support interactions involving digital assets, identity, and data.
- **Smart contract:** Code deployed to a blockchain that executes according to defined rules. Smart contract-specific verification is covered by SCVS.
- **Application security (AppSec):** The practices used to identify, prevent, and manage security risks in software throughout its lifecycle.
- **Software development lifecycle (SDLC):** The stages through which software is specified, designed, built, tested, deployed, operated, and maintained.

These descriptions provide shared context. Individual guides should define specialized terms more precisely where needed.

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

## Documentation maintenance

The README is the entry point for understanding the project's purpose, scope, terminology, audience, and contribution process. Keep it concise enough to orient new readers while linking to detailed guidance in the `guides/` directory.

When maintaining this repository:

- **Keep project metadata aligned.** Ensure the README, GitHub repository description and topics, OWASP project metadata, and project website describe the same purpose and scope.
- **Use consistent terminology.** Define important terms once where practical, use them consistently across guides, and explain specialized terms in their relevant context.
- **Maintain clear scope boundaries.** Add or revise coverage descriptions when the project takes on new areas; distinguish this project's application and system security focus from related OWASP standards such as SCVS.
- **Prefer modular documentation.** Put detailed, topic-specific material in individual guides and link to it from the project overview rather than allowing the README to become a duplicate of the knowledge base.
- **Use traceable references.** Prefer authoritative technical documentation and recognized security resources. Review links and references when content changes.
- **Review changes for consistency.** Check that new or revised material fits the project purpose, audience, terminology, and scope, and update cross-references when files move or topics change.
- **Revisit the overview periodically.** Review this README when project priorities, covered technologies, audience, or repository structure materially change.

The GitHub topics are: `appsec`, `blockchain`, `infosec`, `owasp`, `policy`, `sdlc`, `security`, and `web3`. Update this list and the corresponding contextual descriptions if the OWASP repository's topics change.

## License

This repository's content is licensed under the [Apache License, Version 2.0](LICENSE.md). You may use, reproduce, and distribute the licensed materials in accordance with the terms and conditions in that file. Please review [LICENSE.md](LICENSE.md) for the complete license text, permissions, and conditions.
