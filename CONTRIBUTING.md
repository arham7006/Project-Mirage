# Contributing to MIRAGE

First off, thank you for considering contributing to Project-Mirage! It's people like you that make this project such a great tool for the security community.

## How Can I Contribute?

### 1. New Deception Scenarios
The core value of MIRAGE lies in its traps. If you have engineered a novel honeypot, bait credential, or misdirection technique, please submit it to the `/scenarios` directory. Ensure your submission includes:
- The code/scripts required to deploy the trap.
- A `README.md` explaining the psychology of the trap and what specific attacker behaviors it exploits.

### 2. Deployment Scripts
We aim to make deploying the deception mesh as frictionless as possible across all major cloud providers. If you can optimize our existing Terraform, CloudFormation, or Kubernetes manifests, pull requests are highly encouraged!

## Pull Request Process

1. Fork the repository and create your branch from `main`.
2. Test your deployment scripts or scenarios locally to ensure they do not introduce actual vulnerabilities into a host environment.
3. Issue a Pull Request detailing your changes. A maintainer will review your PR, and once approved, it will be merged into the mesh.

Welcome to the team. Let's build the future of proactive defense.
