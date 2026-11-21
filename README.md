# CodeHawks Security Portfolio

![Smart Contract Security](https://img.shields.io/badge/Focus-Smart%20Contract%20Security-blue)
![Platform](https://img.shields.io/badge/Platform-CodeHawks-purple)
![Education](https://img.shields.io/badge/Learning-Cyfrin%20Updraft-orange)
![License](https://img.shields.io/badge/License-No%20License-lightgrey)

A curated portfolio of smart-contract security audit reports completed through **Cyfrin Updraft** and **CodeHawks**.

This repository documents security reviews of Solidity applications across DeFi, lending, raffles, password storage, and token swapping.

## Audit Reports

| Project | Report | Area of Review |
|---|---|---|
| PasswordStore | [PasswordStore-Audit-2026.pdf](./PasswordStore-Audit-2026.pdf) | Password storage and access control |
| PuppyRaffle | [PuppyRaffle-Audit-2026.pdf](./PuppyRaffle-Audit-2026.pdf) | Randomness, raffle lifecycle, and withdrawals |
| T-Swap | [5-t-swap-Audit-2026.pdf](./5-t-swap-Audit-2026.pdf) | Automated market maker and token swaps |
| Thunder Loan | [6-thunder-loan-Audit-2026.pdf](./6-thunder-loan-Audit-2026.pdf) | Flash loans, lending, and protocol accounting |

## Focus Areas

My audit process focuses on identifying vulnerabilities and protocol risks, including:

- Access-control flaws
- Reentrancy
- Integer overflow and underflow
- Incorrect protocol accounting
- Unsafe external calls
- Oracle and price-feed manipulation
- Weak or predictable randomness
- Denial-of-service vectors
- Business-logic and invariant violations
- DeFi economic attacks
- Gas optimization opportunities

## Audit Methodology

1. Review the project's documentation and expected behavior.
2. Establish core invariants and identify trust assumptions.
3. Map contracts, functions, users, roles, and external interactions.
4. Manually inspect the code for known vulnerability patterns.
5. Analyze state transitions and edge cases.
6. Use testing and tooling to validate findings.
7. Classify findings by severity and impact.
8. Document reproducible proof-of-concepts and recommendations.

## Tools and Technologies

- Solidity
- Foundry
- Slither
- Manual code review
- Property-based and fuzz testing
- CodeHawks
- Cyfrin Updraft
- Git and GitHub

## Repository Structure

```text
.
├── 5-t-swap-Audit-2026.pdf
├── 6-thunder-loan-Audit-2026.pdf
├── PasswordStore-Audit-2026.pdf
└── PuppyRaffle-Audit-2026.pdf
```

## Learning Resources

- [Cyfrin Updraft](https://updraft.cyfrin.io/)
- [CodeHawks](https://codehawks.cyfrin.io/)
- [Solidity Documentation](https://docs.soliditylang.org/)
- [Smart Contract Security Field Guide](https://scsfg.io/)
- [Solidity by Example](https://solidity-by-example.org/)

## Disclaimer

These reports are provided for educational and portfolio purposes. They demonstrate learning and security-review work performed on specific audit challenges. Findings may not represent a complete or production-ready assurance of a protocol's security.

A smart-contract audit does not guarantee that a system is free of vulnerabilities.

## Author

**stash21x-crypto**

- GitHub: [@stash21x-crypto](https://github.com/stash21x-crypto)

## Contributing

Suggestions and educational discussions are welcome:

1. Open an issue.
2. Describe the proposed improvement or finding.
3. Include relevant context and evidence.
4. Keep discussions constructive and technically accurate.

## License

No license has been specified for this repository. Please do not reuse or redistribute the audit reports without the author's permission.
```
