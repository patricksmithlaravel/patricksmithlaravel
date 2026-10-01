<div align="center">

<img src="https://raw.githubusercontent.com/patricksmithlaravel/patricksmithlaravel/main/assets/header.svg" alt="patricksmithlaravel - Rust, Python and TypeScript developer" width="100%" />

<br/>

**Developer building wallet and explorer tooling for the [Mochimo](https://mochimo.org/) chain, plus API and research tools on the side.**

![Rust](https://img.shields.io/badge/Rust-2a2233?style=for-the-badge&logo=rust&logoColor=ffb347) ![TypeScript](https://img.shields.io/badge/TypeScript-2a2233?style=for-the-badge&logo=typescript&logoColor=ffb347) ![Python](https://img.shields.io/badge/Python-2a2233?style=for-the-badge&logo=python&logoColor=fff) ![HTML](https://img.shields.io/badge/HTML-2a2233?style=for-the-badge&logo=html5&logoColor=fff)

</div>

---

## `whoami`

<!-- Replace this with a few sentences in your own voice: what you do, what you care about, what you're working on now. -->

Most of my public work right now is on Mochimo v3, a post-quantum chain that signs transactions with WOTS+ one-time signatures. Outside Mochimo, I build API testing tools in Python and work on the Voynich manuscript challenge.

---

## Mochimo tooling

- **[mcm-rust-cli-wallet](https://github.com/patricksmithlaravel/mcm-rust-cli-wallet)** (Rust): A command-line wallet for Mochimo v3, written in pure Rust with no C toolchain. It signs with WOTS+ one-time signatures and uses 40-byte `tag||hash` addresses. Keys live in an encrypted keystore whose index only moves forward, so the wallet never reuses a one-time key. It talks to the network through a Mesh API client.
- **[mcm-rust-cli-windows](https://github.com/patricksmithlaravel/mcm-rust-cli-windows)** (Rust): The same wallet, extended to build for Windows alongside Linux and macOS. The Windows build compiles but hasn't been run on Windows yet.
- **[mcm-block-explorer](https://github.com/patricksmithlaravel/mcm-block-explorer)** (HTML): A lightweight Mochimo block explorer.

---

## Other projects

- **[PostPy](https://github.com/patricksmithlaravel/PostPy)** (Python): A library for API automation and testing. It makes HTTP requests, organizes endpoints into collections, handles environment variables, and runs a mock server for prototyping.
- **[voynich](https://github.com/patricksmithlaravel/voynich)** (Python): Public research workspace, evidence, and grading methodology for the Voynich manuscript challenge at [voynich.win](https://voynich.win).

---

## Toolbox

- **Languages** · Rust · TypeScript · Python · HTML / CSS
- **Crypto / chain** · WOTS+ · Mochimo v3 · Mesh API
- **Platforms** · Linux · macOS · Windows
