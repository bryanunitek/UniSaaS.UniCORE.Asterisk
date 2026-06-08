# UniSaaS.UniCORE.Asterisk

**SCAFFOLD-ANCHOR repository — initial scaffold 2026-06-04.**

Full scaffolding, upstream-fork integration, and source-code work all pending a fresh dedicated kickoff arc. This initial commit exists to lock the repository's identity, licence position, and place in the UniCORE Sanity Check fleet so the work cannot be forgotten.

Author: **Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom.**
First commit: **2026-06-04 16:45 UTC.**

---

## What this repository is

`bryanunitek/UniSaaS.UniCORE.Asterisk` is the **Asterisk** family member: SaaS-deployment-shape public gift surface. Documentation today; source code at certification.

**Family purpose:** Open-source PBX, telephony, and IVR platform. Asterisk delivers voice routing, conferencing, SIP trunking, and IVR flows on UniCORE-deployed infrastructure.

**Role in UniCORE:** Telephony substrate — UniCORE.GVB substrate-services consume Asterisk to deliver enterprise voice communications on SaaS deployments.

**Deployment shape:** This is the **SaaS-shape** member of the family. It tracks the same upstream codebase as [`UniCORE.Asterisk`](https://github.com/bryanunitek/UniCORE.Asterisk) (on-prem shape) but carries SaaS-specific configuration, multi-tenant isolation patterns, and cloud-native deployment artefacts.

---

## Upstream

- **Upstream project:** [https://github.com/asterisk/asterisk](https://github.com/asterisk/asterisk)
- **Upstream licence:** GPL-2.0 (with Asterisk Linking Exception)
- **Our relationship:** Fork-and-extend. Upstream codebase is consumed verbatim under its original licence; our code additions carry the same GPL-2.0; our documentation additions sit under CC BY 4.0.

---

## Platforms

Windows · Linux · macOS · iOS · Android

---

## Family — the four-repo pattern

- [`UniCORE.Asterisk`](https://github.com/bryanunitek/UniCORE.Asterisk) — public on-prem-deployment-shape gift surface
- `bryanunitek/UniSaaS.UniCORE.Asterisk` — public SaaS-deployment-shape gift surface ← **this repo**
- `bryanunitek/UniCORE.Asterisk-Claw` (private) — on-prem-shape working repository
- `bryanunitek/UniSaaS.UniCORE.Asterisk-Claw` (private) — SaaS-shape working repository

---

## Status

**SCAFFOLD-ANCHOR** as of 2026-06-04. See [`STATUS.md`](STATUS.md).

---

## Contact

- **Public discussion:** [GitHub Discussions](https://github.com/bryanunitek/UniSaaS.UniCORE.Asterisk/discussions)
- **Private contact:** [LinkedIn — Bryan Fred](https://www.linkedin.com/in/bryan-fred-02209753/)

---

*Author: Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom. Public. Given, not sold. Irrevocable.*
