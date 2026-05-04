<div align="center">

<img
  src="https://raw.githubusercontent.com/vril-labs/.github/main/profile/assets/logo.svg"
  width="160"
  height="160"
  alt="VRIL LABS — implosion energy mark"
/>

<h1>VRIL&nbsp;LABS</h1>

<p><strong>Post-Quantum Sovereign Technology</strong></p>

<p><em>Post-quantum cryptography &nbsp;·&nbsp; Neural intelligence &nbsp;·&nbsp; Entropy compression</em></p>

<br/>

<p><sup>ANCIENT KNOWLEDGE &nbsp;·&nbsp; FUTURE TECHNOLOGY</sup></p>

<p><em>Where ancient wisdom meets computational power.<br/>
Bridging the gap between primordial forces and modern science.</em></p>

<br/>

[![vril.li](https://img.shields.io/badge/vril.li-visit-1fe8a8?style=flat-square&labelColor=0b0c0b&color=1fe8a8)](https://vril.li)
[![Research](https://img.shields.io/badge/Research-Papers%20%26%20Proofs-1fe8a8?style=flat-square&labelColor=0b0c0b&color=1fe8a8)](https://vril.li#research)
[![Contact](https://img.shields.io/badge/Contact-Secure%20Channel-1fe8a8?style=flat-square&labelColor=0b0c0b&color=1fe8a8)](https://vril.li#contact)

</div>

---

## Sovereign Components

> Four precision-engineered systems. Each purpose-built to be structurally superior to anything that came before.

| Component | Domain | Key Specs |
|---|---|---|
| **[VRIL-KEM](https://vril.li)** | Post-Quantum Cryptography | 384-bit quantum security · MLWE n=4096 · 7-layer CVKDF · IND-CCA2 (EasyCrypt) |
| **[VRIL-AI](https://vril.li)** | Neural Intelligence | betterFANN architecture · WASM runtime · UiLLM interface · typed tensor flows |
| **[VRIL-ZIP](https://vril.li)** | Entropy Compression | 7-layer Fibonacci cascade · φ-weighted · lossless · CVKDF-integrated |
| **VRIL-PROXY / MESH / CERT / HSM** | Ecosystem | Sovereign infrastructure stack — active development |

---

## The Cryptographic Core

VRIL-KEM is built on **Module-Learning-with-Errors** with parameters chosen to defeat both classical and quantum adversaries.

```
Ring dimension  n = 4096    NTT-friendly prime  q = 12289
Module rank     k = 7       CBD noise parameter η = 3
CVKDF layers    7           Fibonacci weights   [1,1,2,3,5,8,13]
```

Every design decision traces to a named structural flaw in prior implementations:

- **CVKDF One-Wayness** — Classical linear key-compression replaced by 7-layer Fibonacci-weighted geometric cascade. EasyCrypt-proven 2⁻¹²⁸ bound.
- **HI-Gaussian vs CBD** — Hierarchical-Interleaved Gaussian with golden-ratio scaling over standard centered binomial distribution.
- **AVX2 NTT Butterflies** — 16-way SIMD delivers 6–7× throughput. FPGA achieves 40µs on VU13P — 400× over software baseline.
- **Constant-Time Masking** — Full DPA/timing resistance. 1st & 3rd order Boolean/arithmetic masking. TVLA-verified.

---

## Performance Benchmarks

| Variant | Security | pk Size | Latency (AVX2) | Use Case |
|---|---|---|---|---|
| VRIL-2048-5 | 256-bit | ~15 KB | < 2ms | Embedded / IoT |
| **VRIL-4096-7** | **384-bit** | **~46 KB** | **2.4ms** | **Production (default)** |
| VRIL-8192-11 | 512-bit | ~180 KB | < 8ms | Ultra-High Security |

---

## Research Log

| Period | Phase | Milestone |
|---|---|---|
| 2025 Q4 | Foundation | VRIL-KEM Core Specification — MLWE parameters, CVKDF introduced |
| 2026 Q1 | Cryptanalysis | EasyCrypt IND-CCA2 · Coq correctness · Jasmin constant-time |
| 2026 Q1 | Performance | AVX2 16-way SIMD · FPGA RTL complete · ASIC targets documented |
| 2026 Q1 | Security | DPA/timing resistance · Boolean & arithmetic masking · maskVerif |
| 2026 Q1 | Integration | TLS 1.3 · OpenSSL provider · Hybrid X25519+VRIL-KEM · < 5ms overhead |
| 2026 Q2 | Upcoming | VRIL-AI v1 · VRIL-ZIP Beta · IETF draft for VRIL-KEM TLS extension |

---

## Philosophy

```
01  Proof-First Design      Security is not claimed — it is machine-checked.
02  Hardware to the Metal   AVX2 → FPGA → ASIC. Software descends to silicon.
03  Cohesive Ecosystem      CVKDF in KEM is the same engine powering VRIL-ZIP.
04  Side-Channel Resistant  Constant-time arithmetic from the first line of code.
05  Open Derivation         Every improvement traces to a specific, named flaw.
06  Production from Day One No mocks. No TODOs. No placeholders. It ships.
```

---

<div align="center">

**[vril.li](https://vril.li) &nbsp;·&nbsp; [Research](https://vril.li#research) &nbsp;·&nbsp; [Contact](https://vril.li#contact)**

<sub>© 2026 VRIL LABS — Post-Quantum Sovereign Technology</sub>

</div>
