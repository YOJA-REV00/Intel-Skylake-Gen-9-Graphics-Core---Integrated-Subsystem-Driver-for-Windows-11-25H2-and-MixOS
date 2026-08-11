# Intel-Skylake-Gen-9-Graphics-Core---Integrated-Subsystem-Driver-for-Windows-11-25H2-and-MixOS
A little customized Intel DCH driver focused on performance optimizations and native compatibility for Windows 11 & MixOS systems. (Based on 31.0.101.2115)

## Driver Information
* **Base Architecture:** Intel Gen 9 (Skylake / Desktop GT2)
* **Official Branch Base:** 31.0.101.2115 (Legacy DCH)
* **Custom Driver Version:** 31.0.101.4509
* **Driver Date:** August 11, 2026
* **Digital Signer:** MixOS Dev.
* **Target OS:** Windows 11 (22H2, ..... 25H2) / Windows 10

## Key Modifications & Tweaks
* **Windows 11 Target Override:** Forced native OS installation matching platform targets (`NTamd64.10.0...22000`).
* **Frame Optimization:** Injected `CBRenderAfterFlip` to significantly reduce frame presentation latency.
* **Modern Windows Display Architecture:** Enabled `Kmd_EnableModernDisplayEngine` for optimal Windows 11 DWM interaction.
* **Dynamic VRAM Scaling:** Unlocked resource allocation with `GmmCustomDVMTAllocation` and `IncreaseSystemMemoryDynamicAllocation` to bypass strict OEM limits under heavy 3D loads.

## Installation Instructions (For Testers)
1. Download the repository and locate the `MixOS_Dev.cer` certificate file.
2. Double-click on `MixOS_Dev.cer` and click on **Install Certificate**.
3. Select **Local Machine** (Equipo local) and choose "**Place all certificates in the following store**".
4. Install it into **Trusted Root Certification Authorities** (Entidades de certificación de raíz de confianza).
5. Repeat the install process and place it also into **Trusted Publishers** (Editores de confianza).
6. Open Device Manager, select your Intel GPU, choose "Update Driver", and browse to the extracted `Graphics` folder.
