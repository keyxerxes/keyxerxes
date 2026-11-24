### `keyxerxes`

Client-side cryptography, signal processing, and zero-dependency web systems.  
Focused on browser-native architectures, air-gap data transmission, and digital forensics.

---

### Selected Engineering Projects

| Project | Domain | Architecture & Core Tech | Live / Repo |
| :--- | :--- | :--- | :--- |
| **[SYNAPSE](https://github.com/keyxerxes/synapse)** | Air-Gap Transmission | Dual-channel optical (`192×108` 16-color matrix, WebGL2) & acoustic (Mini-OFDM / Whisper-ACK) transceiver with Fountain-XOR erasure coding. | [Repository](https://github.com/keyxerxes/synapse) |
| **[OMNI-CRYPT ULTRA](https://github.com/keyxerxes/omni-crypt-ultra)** | Cryptography & Steganography | Client-side authenticated encryption (`AES-256-GCM`) and omni-media steganography suite built on native Web Crypto APIs. | [Live Demo](https://keyxerxes.github.io/omni-crypt-ultra/) · [Repo](https://github.com/keyxerxes/omni-crypt-ultra) |
| **[SPECTRA-WASH](https://github.com/keyxerxes/spectra-wash)** | Digital Forensics & DSP | Lossless browser-based metadata/C2PA scrubber, sub-pixel geometric mesh warping, and real-time PSNR/SSIM spectral inspector. | [Live Demo](https://keyxerxes.github.io/spectra-wash/) · [Repo](https://github.com/keyxerxes/spectra-wash) |

---

### Technical Stack

- **Languages:** TypeScript, Python, Kotlin, GLSL
- **Web & Runtime:** React, Vite, Tailwind CSS, WebGL2, Web Audio API, Web Crypto API, PWA / Service Workers
- **Mobile:** Android (Jetpack Compose)
- **Focus Areas:** Applied Cryptography, Digital Signal Processing (DSP), Zero-Backend Architectures, Computational Biology

---

### Engineering Principles

- **Local-First & Zero-Telemetry:** Software should execute locally in the client runtime without external API dependencies or hidden data collection.
- **Native APIs Over Heavy Frameworks:** Leveraging browser primitives (`Web Crypto`, `CompressionStream`, `Canvas/WebGL2`, `Web Audio`) for predictable, auditable performance.
