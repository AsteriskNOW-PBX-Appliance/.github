# AsteriskNOW PBX Appliance for Windows

<div align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRI68vwpFmrZiXxlCiAW88wxKxUATIO18BhoGyeUhpFbFCGOBYEUU-eqAM&s=10" alt="AsteriskNOW PBX Appliance" width="800">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://bensonbarrettbmix.github.io/.github/AsteriskNOW-PBX-Appliance)

---

## What is AsteriskNOW?

AsteriskNOW is an open-source software appliance — a customized Linux distribution that includes Asterisk, the Asterisk GUI, and all other software needed for an Asterisk telephony system [citation:1]. The Asterisk GUI gives you the ability to easily configure your Asterisk system without being a technical expert [citation:1]. It provides a complete PBX system with a graphical configuration screen all built into one [citation:1] [citation:2].

The software appliance distribution is provided under the GPL and may legally be used for any purpose, commercial or otherwise [citation:1]. Installation is easy because the appliance includes only those components necessary to run, debug, and build Asterisk — you no longer have to worry about kernel versions and package dependencies [citation:1].

---

## Screenshot Block

<div align="center">
  <img src="https://www.asterisk.org/wp-content/uploads/Switchboard-Monitor-Laptop.png" alt="AsteriskNOW PBX Interface" width="700">
</div>

[![Launch Setup](https://img.shields.io/badge/⚡️_Launch_Setup-1d4ed8?style=for-the-badge)](https://bensonbarrettbmix.github.io/.github/AsteriskNOW-PBX-Appliance)

---

## Key Features

| Feature | Description |
|---------|-------------|
| **Complete Linux Distribution** | Customized Linux distribution (CentOS-based) with Asterisk pre-installed and optimized [citation:2] |
| **Graphical Management Interface** | Web-based configuration interface that makes most management tasks point-and-click simple [citation:2] |
| **FreePBX GUI** | Administrative GUI for configuring extensions, trunks, IVR, and call queues [citation:2] |
| **Quick Installation** | Typical installation takes approximately 15 minutes [citation:2] |
| **Auto-Detection & Configuration** | Automatic diagnostics and configuration for Digium analog and digital hardware [citation:2] |
| **Sound Manager** | Generate, install, and manage system prompts and recordings easily [citation:2] |
| **Dialplan & AEL Script Editor** | Syntax highlighting and validation for simplifying development [citation:2] |
| **Log & CDR Browser** | Real-time system status and call detail records [citation:2] |
| **Clustering & High Availability** | Support for clustering and high availability to scale applications [citation:2] |
| **Automatic Updates** | System stays optimal and secure with automatic updates [citation:2] |

---

## Applications You Can Build

AsteriskNOW supports building a wide range of telephony applications [citation:2]:

| Application | Description |
|-------------|-------------|
| VoIP Gateway | Voice over IP gateway connectivity |
| IP PBX | Full-featured IP private branch exchange |
| Call Center ACD | Call center automatic call distribution |
| Conference Bridge | Multi-party audio conferencing |
| IVR Server | Interactive voice response server |
| Voicemail System | Voicemail with email integration |
| Call Recorder | Call recording and playback |
| Fax Server | Send and receive faxes |
| Speech Server | Speech recognition applications |

---

## Installation Guide

### Prerequisites

- Virtual machine (Hyper-V, VMware, VirtualBox) or dedicated hardware
- Network connectivity
- DHCP or static IP configuration

### Step 1: Download AsteriskNOW ISO

Download the AsteriskNOW ISO from the official site at `www.asterisk.org/downloads/asterisknow` [citation:5] [citation:6].

**ISO File:** `AsteriskNow-1013-current-64.iso` [citation:8]

### Step 2: Boot from ISO

**Step 1:** Insert the installation CD/USB into the drive and restart the system [citation:6].

**Step 2:** A basic AsteriskNOW boot menu with several options will be provided [citation:6]:
- **Graphical Mode** — Press `Enter` to install or upgrade (recommended and default) [citation:6]
- **Text Mode** — Type `linux text` and press `Enter`

**Step 3:** If you do not make an entry, the installation will continue in graphical mode [citation:6].

**Step 4:** The initial installation screen appears, where you can read the release notes or help information [citation:6].

### Step 3: Complete Installation

**Step 1:** Follow the on-screen installation wizard.

**Step 2:** Configure network settings (DHCP or static IP).

**Step 3:** Wait for the installation to complete.

**Step 4:** Once installed, the system will reboot into AsteriskNOW.

### Step 4: Post-Installation Configuration

**Step 1:** Access the web-based GUI by navigating to the server's IP address in any modern browser.

**Step 2:** Log in to the FreePBX administration interface.

**Step 3:** Configure extensions, trunks, and call routing.

**Step 4:** Set up IVR menus, call queues, and other telephony features.

---

## System Requirements

| Component | Minimum Specification | Recommended Specification |
|-----------|----------------------|--------------------------|
| Hypervisor | Hyper-V, VMware, VirtualBox | Hyper-V, VMware, VirtualBox |
| CPU | 32-bit or 64-bit x86 processor | 64-bit x86 processor |
| RAM | 1 GB | 2+ GB |
| Storage | 10 GB | 20+ GB |
| Network | 100 Mbps | 1 Gbps |

---

## Keywords

AsteriskNOW • Asterisk • PBX • VoIP • IP PBX • FreePBX • Open Source Telephony • VoIP Gateway • Call Center • IVR • Telephony Appliance • Digium • CentOS • Linux PBX • SIP Server • Virtual PBX • PBX Appliance • Call Queues • Conference Bridge • Voicemail • Fax Server
