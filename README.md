<div align="center">

<img src="https://raw.githubusercontent.com/patricksmithlaravel/patricksmithlaravel/main/assets/header.svg" alt="patricksmithlaravel - Rust, Python, TypeScript and JavaScript developer" width="100%" />

<br/>

**Developer building wallet and explorer tooling for the [Mochimo](https://mochimo.org/) chain, a block builder for Ansible, and API testing tools for Python.**

![Rust](https://img.shields.io/badge/Rust-2a2233?style=for-the-badge&logo=rust&logoColor=ffb347) ![Python](https://img.shields.io/badge/Python-2a2233?style=for-the-badge&logo=python&logoColor=fff) ![TypeScript](https://img.shields.io/badge/TypeScript-2a2233?style=for-the-badge&logo=typescript&logoColor=ffb347) ![JavaScript](https://img.shields.io/badge/JavaScript-2a2233?style=for-the-badge&logo=javascript&logoColor=ffb347) ![Ansible](https://img.shields.io/badge/Ansible-2a2233?style=for-the-badge&logo=ansible&logoColor=fff)

</div>

---

## `whoami`

<!-- Replace this with a few sentences in your own voice: what you do, what you care about, what you're working on now. -->

Most of my public work right now is on Mochimo v3, a post-quantum chain that signs transactions with WOTS+ one-time signatures, and on network automation with Ansible. I also build API testing tools in Python.

---

## Mochimo tooling

- **[mcm-rust-cli-wallet](https://github.com/patricksmithlaravel/mcm-rust-cli-wallet)** (Rust): A command-line wallet for Mochimo v3, written in pure Rust with no C toolchain. It signs with WOTS+ one-time signatures and uses 40-byte `tag||hash` addresses. Keys live in an encrypted keystore whose index only moves forward, so the wallet never reuses a one-time key. It talks to the network through a Mesh API client.
- **[mcm-rust-cli-windows](https://github.com/patricksmithlaravel/mcm-rust-cli-windows)** (Rust): The same wallet, extended to build for Windows alongside Linux and macOS. The Windows build compiles but hasn't been run on Windows yet.
- **[mcm-block-explorer](https://github.com/patricksmithlaravel/mcm-block-explorer)** (HTML): A lightweight Mochimo block explorer.

---

## Automation and testing

- **[scransible](https://github.com/patricksmithlaravel/scransible)** (JavaScript): A block builder for Ansible, aimed at network automation as much as servers. Plays, tasks and keywords snap together like Scratch blocks, and each block is exactly one piece of Ansible YAML. It imports existing playbooks, roles and inventories, exports a playbook or a whole project as a `.zip`, and ships module sets for Cisco IOS and NX-OS. Try it at [www.scransible.io](https://www.scransible.io/).
- **[PostPy](https://github.com/patricksmithlaravel/PostPy)** (Python): A Postman-style API testing tool for Python. It runs collections of HTTP requests with assertions and serves mock APIs from a YAML file. A failed assertion exits non-zero, so collections can run in CI. Recent fixes closed a remote-code-execution bug in the mock server and stopped credentials from following redirects to other hosts.

---

## Toolbox

- **Languages** · Rust · Python · TypeScript · JavaScript · HTML / CSS
- **Crypto / chain** · WOTS+ · Mochimo v3 · Mesh API
- **Automation** · Ansible · Cisco IOS · Cisco NX-OS
- **Platforms** · Linux · macOS · Windows
