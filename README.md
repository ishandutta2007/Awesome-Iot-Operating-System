<p align="center">
  <img src="assets/banner.svg" alt="Awesome IoT Operating Systems Banner" width="100%">
</p>

# 🌐 Awesome IoT Operating Systems

<p align="left">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://awesome.re/badge.svg" alt="Awesome List"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Iot-Operating-System"><img src="https://img.shields.io/badge/IoT_OS-Ecosystem-blue.svg" alt="IoT Operating System Ecosystem"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

A comprehensive, curated directory of top **IoT Operating Systems (IoT OS)** 📟, Real-Time Operating Systems (RTOS) ⚡, Embedded Linux distributions 🐧, and secure IoT microkernels 🛡️ for microcontrollers, edge gateways, and connected hardware.

*Last updated: October 2026* 📅

---

## 📑 Table of Contents

- [📊 Overview & Market Size](#-overview--market-size)
- [☁️ SaaS & Commercial Platforms](#️-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [📈 Star History](#-star-history)
- [⚠️ Disclaimer](#️-disclaimer)

---

## 📊 Overview & Market Size

The global **IoT Operating System market** 🌐 is valued at approximately **\$2.3 Billion to \$7.0 Billion (2026)** with an estimated Compound Annual Growth Rate (CAGR) of **13% to 35%** 📈.

**Market Dynamics:** The sector is **highly fragmented** 🧩 at the embedded device and hardware layer due to heterogeneous silicon architectures (Cortex-M, RISC-V, ESP32, AVR, x86) and specialized operational constraints (ultra-low power vs. high performance). However, it exhibits **increasing concentration** 🏢 at the cloud management plane around major cloud and enterprise software giants (Microsoft, Amazon AWS, Wind River/Aptiv) offering end-to-end edge-to-cloud security and device lifecycle management.

---

## ☁️ SaaS & Commercial Platforms

| Platform | Enterprise Owner | Company Size (Revenue / Valuation) | Starting Paid Tier Pricing | Free Tier / Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Amazon FreeRTOS / AWS IoT](https://aws.amazon.com/freertos/)** | Amazon / AWS | **\$620B+ Revenue** (~\$1.8T+ Valuation) | **\$0.08 per million connection minutes** (AWS IoT Core pricing after free tier) | **12 Months Free Tier:** 2.25M connection minutes/month, 500k messages/month, 225k shadow/registry ops/month | Amazon-supported RTOS libraries optimized for secure connectivity to AWS IoT Core and cloud services. ☁️ |
| **[Azure Sphere OS](https://azure.microsoft.com/products/azure-sphere/)** | Microsoft | **\$245B+ Revenue** (~\$3.1T+ Valuation) | **\$8.60 per chip** (One-time license cost built into certified MCU chip purchase) | **No monthly fee:** Software/OS updates and security services included for life of chip; \$200 Azure cloud trial credit for new accounts | Hardware-rooted Linux OS & security platform bundled with certified silicon for lifecycle updates and zero-trust security. 🔒 |
| **[VxWorks](https://www.windriver.com/products/vxworks)** | Wind River Systems (Aptiv PLC) | **\$400M+ Revenue** (\$4.3B Acquisition Valuation by Aptiv) | **\$18,500 per developer seat** (Base enterprise license quote) | **30-Day Evaluation License:** Available upon enterprise request for qualified projects | Industry-leading commercial RTOS built for safety-critical aerospace, defense, automotive, and industrial automation. 🚀 |
| **[Embedded Linux (Wind River Linux)](https://www.windriver.com/products/linux)** | Wind River Systems (Aptiv PLC) | **\$400M+ Revenue** (\$4.3B Acquisition Valuation by Aptiv) | **\$10,000 per project/year** (Commercial LTS subscription without per-device royalties) | **Free Community Source:** Community-aligned source code available for evaluation without commercial SLA | Production-grade commercial Embedded Linux distribution with long-term maintenance, CVE vulnerability monitoring, and enterprise support. 🐧 |

---

## 🔓 Open-Source GitHub Projects

Curated open-source IoT operating systems and RTOS kernels sorted by GitHub stargazers count (descending) 🌟.

- **[OpenWrt](https://github.com/openwrt/openwrt)**  
  [![Stars](https://img.shields.io/github/stars/openwrt/openwrt?style=social&color=white)](https://github.com/openwrt/openwrt/stargazers)  
  Linux operating system targeting embedded network devices and IoT gateways, replacing vendor firmware with customizable package management 📡.

- **[MicroPython](https://github.com/micropython/micropython)**  
  [![Stars](https://img.shields.io/github/stars/micropython/micropython?style=social&color=white)](https://github.com/micropython/micropython/stargazers)  
  Lean and efficient implementation of Python 3 optimized to run on microcontrollers and in constrained environments 🐍.

- **[ESP-IDF](https://github.com/espressif/esp-idf)**  
  [![Stars](https://img.shields.io/github/stars/espressif/esp-idf?style=social&color=white)](https://github.com/espressif/esp-idf/stargazers)  
  Official IoT Development Framework for Espressif SoCs (ESP32 series), built on top of FreeRTOS with extensive Wi-Fi/Bluetooth stacks 📶.

- **[Zephyr RTOS](https://github.com/zephyrproject-rtos/zephyr)**  
  [![Stars](https://img.shields.io/github/stars/zephyrproject-rtos/zephyr?style=social&color=white)](https://github.com/zephyrproject-rtos/zephyr/stargazers)  
  Modular, secure, open-source RTOS hosted by the Linux Foundation, supporting multi-architecture hardware, Bluetooth Low Energy (BLE), Thread, and low-power IoT applications ⚡.

- **[RT-Thread](https://github.com/RT-Thread/rt-thread)**  
  [![Stars](https://img.shields.io/github/stars/RT-Thread/rt-thread?style=social&color=white)](https://github.com/RT-Thread/rt-thread/stargazers)  
  Open-source real-time operating system with rich software components, POSIX thread support, and small memory footprint for MCU IoT hardware 🧠.

- **[FreeRTOS](https://github.com/FreeRTOS/FreeRTOS)**  
  [![Stars](https://img.shields.io/github/stars/FreeRTOS/FreeRTOS?style=social&color=white)](https://github.com/FreeRTOS/FreeRTOS/stargazers)  
  Market-leading open-source real-time operating system kernel for microcontrollers, featuring small footprint, high portability, and extensive silicon vendor adoption 🔌.

- **[Tock OS](https://github.com/tock/tock)**  
  [![Stars](https://img.shields.io/github/stars/tock/tock?style=social&color=white)](https://github.com/tock/tock/stargazers)  
  Embedded operating system designed for microcontrollers, written in Rust to provide memory safety and multiprogramming isolation 🦀.

- **[RIOT OS](https://github.com/RIOT-OS/RIOT)**  
  [![Stars](https://img.shields.io/github/stars/RIOT-OS/RIOT?style=social&color=white)](https://github.com/RIOT-OS/RIOT/stargazers)  
  Developer-friendly open-source OS for ultra-low-power IoT devices with C/C++ support, full IPv6 (6LoWPAN, RPL) network stack, and standard POSIX-like APIs 🔋.

- **[ARM Mbed OS](https://github.com/ARMmbed/mbed-os)**  
  [![Stars](https://img.shields.io/github/stars/ARMmbed/mbed-os?style=social&color=white)](https://github.com/ARMmbed/mbed-os/stargazers)  
  Open-source embedded operating system designed specifically for Arm Cortex-M devices, providing security, storage, and connectivity drivers 🤖.

- **[Apache NuttX](https://github.com/apache/nuttx)**  
  [![Stars](https://img.shields.io/github/stars/apache/nuttx?style=social&color=white)](https://github.com/apache/nuttx/stargazers)  
  POSIX-compliant mature open-source real-time operating system scalable from 8-bit to 32-bit/64-bit embedded microcontrollers ⚙️.

- **[Hubris OS](https://github.com/oxidecomputer/hubris)**  
  [![Stars](https://img.shields.io/github/stars/oxidecomputer/hubris?style=social&color=white)](https://github.com/oxidecomputer/hubris/stargazers)  
  Lightweight microkernel RTOS written in Rust by Oxide Computer Company, built for high-reliability embedded system control 🛡️.

- **[Contiki-NG](https://github.com/contiki-ng/contiki-ng)**  
  [![Stars](https://img.shields.io/github/stars/contiki-ng/contiki-ng?style=social&color=white)](https://github.com/contiki-ng/contiki-ng/stargazers)  
  Next-generation open-source operating system focused on low-power wireless sensor networks and IoT mesh communication standards 🕸️.

- **[TinyOS](https://github.com/tinyos/tinyos-main)**  
  [![Stars](https://img.shields.io/github/stars/tinyos/tinyos-main?style=social&color=white)](https://github.com/tinyos/tinyos-main/stargazers)  
  Component-based, event-driven operating system designed for low-power wireless sensor networks (WSN) 📡.

- **[Yocto Project (Poky)](https://github.com/yoctoproject/poky)**  
  [![Stars](https://img.shields.io/github/stars/yoctoproject/poky?style=social&color=white)](https://github.com/yoctoproject/poky/stargazers)  
  Reference distribution and build system tooling for creating custom Linux-based operating systems for embedded hardware and IoT gateways 🛠️.

---

## 🤝 How to Contribute

1. **Fork** the repository 🍴.
2. Add or update entries in `README.md` following the existing format 📝.
3. Ensure open-source entries include the correct GitHub stargazers badge pointing to the repository's `stargazers` page 🏷️.
4. Submit a **Pull Request** with a concise description of your changes 🚀.

---

## 💖 Support & Sponsorship

Thank you for exploring the **Awesome IoT Operating Systems** directory! If you found this list helpful for your research, projects, or hardware deployments, please consider supporting the project:

- ⭐ **Star this repository** to help others discover it!
- 🍴 **Fork and share** it with your fellow firmware engineers and embedded developers.
- ☕ **Buy me a coffee / Sponsor**: If you'd like to support ongoing maintenance and new open-source resource lists, visit my [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

Your support is greatly appreciated! 🙌

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Iot-Operating-System&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Iot-Operating-System&type=date&legend=top-left)

---

## ⚠️ Disclaimer

This repository is a community-curated collection intended for educational and informational purposes 💡. Operating system choice depends on hardware architecture, real-time requirements, safety certifications, and power constraints. Always perform detailed technical evaluation before deploying software to production IoT devices.

---

*Maintained with ❤️ for embedded software engineers, IoT system architects, and firmware developers.*
# Awesome-Iot-Operating-System

Awesome-Iot-Operating-SystemCurated List of SaaS Products & Open-Source GitHub ProjectsFocused on Real-Time Operating Systems (RTOS), Embedded Linux & IoT ConnectivityLast updated: October 2026This repository tracks notable commercial platforms and open-source projects for IoT Operating Systems. These tools help developers build firmware for connected devices—from battery-powered sensors and wearables to industrial gateways and smart home hubs—where deterministic behavior, low power consumption, and secure connectivity are essential.Examples include Azure Sphere OS, Azure RTOS, VxWorks, FreeRTOS, Zephyr RTOS, RIOT OS, Contiki-NG, TinyOS, Embedded Linux, and Mbed OS (the category leaders).Open-source emphasis: The open-source IoT OS ecosystem is exceptionally mature and production-proven. FreeRTOS has been downloaded every 175 seconds and is actively maintained by AWS with Long Term Support (LTS) releases . Zephyr RTOS reached version 4.1 with experimental Rust support and a modular architecture backed by the Linux Foundation . RIOT OS powers low-end embedded devices with a microkernel architecture and 5,535 GitHub stars . Contiki-NG continues the legacy of the original Contiki OS with a 3-clause BSD license and a focus on severely constrained wireless devices . This section documents these production-grade solutions.📖 Table of Contents☁️ SaaS/Hosted Platforms🔓 Open-Source GitHub Projects🤝 How to Contribute⚠️ Disclaimer☁️ SaaS/Hosted Platforms📊 Market Context: The global IoT operating system market is estimated at ~$2.5B in 2026**, growing toward **~$8B by 2032. The sector is moderately fragmented — FreeRTOS dominates the microcontroller RTOS market by download volume, while Azure Sphere OS and Azure RTOS leverage Microsoft's cloud ecosystem, and VxWorks holds strong positions in safety-critical and industrial segments . Critical lifecycle notices: Arm sunsetted Mbed OS in July 2026 — no longer actively maintained . Microsoft announced Azure Sphere retirement with end-of-service set for September 2027; new commitments are not commercially supported and migration planning should be in flight by mid-2026 . Pricing varies dramatically: Azure Sphere MCU pricing is less than $8.95 (one-time, includes OS license and security service) , VxWorks requires custom enterprise licensing with no free version or trial , and Azure RTOS components are largely free and open source with commercial support available through Microsoft .PlatformDescriptionPricing (Starting Tier)Free Tier LimitsCompany SizeAzure Sphere OSMicrosoft's secured IoT platform. Custom Linux-based microcontroller OS combined with certified hardware and cloud security services. Retiring September 2027 .Less than $8.95 one-time per MCU (MediaTek MT3620AN) — includes chip, OS license, and Azure Sphere Security Service .No ongoing fees — one-time cost covers OS updates for the lifetime of the chip . Azure Sphere platform is free to use; you pay for hardware and Azure services consumed .~$281B revenue (Microsoft FY2025)Azure RTOSMicrosoft's real-time operating system suite (formerly ThreadX). Components include ThreadX (kernel), FileX, GUIX, NetX Duo, and USBX .Free and open source (MIT) for most components . Commercial support available through Microsoft.Free to use and modify . No per-device royalties for the open-source components .~$281B revenue (Microsoft FY2025)VxWorksThe gold standard for safety-critical RTOS. Certified for DO-178C, IEC 61508, ISO 26262, and FDA Class III. Used in Mars rovers, medical devices, and avionics .Custom enterprise licensing — quote required. No free version or free trial .No free tier for commercial use. Academic licensing available free of charge for teaching and research programs .Private (Wind River, ~$500M+ revenue est.)Zephyr RTOS (Commercial Support)Linux Foundation-backed RTOS. Zephyr 4.1 adds experimental Rust support, USB MIDI 2.0, and IAR toolchain support .Free and open source (Apache 2.0) . Commercial support available through member companies (Intel, Nordic, NXP, Renesas, etc.) .Free to use and modify . No per-device royalties.Nonprofit (Linux Foundation)🔓 Open-Source GitHub ProjectsRepoDescriptionStarsZephyr RTOS — The fastest-growing open-source RTOS. Apache 2.0 licensed, Linux Foundation backed. Modular architecture with extensive kernel services, multiple scheduling algorithms, memory protection, and native IPv4/IPv6 protocol stack . Zephyr 4.1 adds experimental Rust support, USB MIDI 2.0, and IAR toolchain integration . Supports ARM, RISC-V, x86, Xtensa, ARC, MIPS, SPARC, and OpenRISC .https://img.shields.io/github/stars/zephyrproject-rtos/zephyr?style=social&color=white~13,000FreeRTOS — The most widely deployed RTOS in the world. MIT licensed, downloaded every 175 seconds . Includes kernel plus libraries for connectivity, security, and OTA updates . Supports Symmetric Multiprocessing (SMP) on multi-core microcontrollers . Actively maintained by AWS with LTS releases providing security updates for two years .https://img.shields.io/github/stars/FreeRTOS/FreeRTOS?style=social&color=white~4,000RIOT OS — The friendly OS for IoT. Microkernel architecture with LGPLv2.1 licensing . 5,535 stars, 2,053 forks . Designed for low-end embedded devices too small for Linux . Supports 8-bit, 16-bit, and 32-bit microcontrollers . Real-time multi-threading with a focus on energy efficiency and small memory footprint .https://img.shields.io/github/stars/RIOT-OS/RIOT?style=social&color=white~5,535Contiki-NG — The OS for next-generation IoT devices. 3-clause BSD license . Fork of the original Contiki OS (open-sourced in 2006) . Cross-platform for severely constrained wireless embedded devices . Built-in 6LoWPAN, RPL, and CoAP stacks . Actively maintained with a focus on low-power wireless .https://img.shields.io/github/stars/contiki-ng/contiki-ng?style=social&color=white~1,500TinyOS — The original open-source OS for wireless sensor networks. BSD licensed . Component-based architecture enabling rapid innovation while minimizing code size for severe memory constraints . Written in nesC (a C dialect) . Designed for smartdust, sensor networks, and ubiquitous computing .https://img.shields.io/github/stars/tinyos/tinyos-main?style=social&color=white~500Apache NuttX — Apache's mature RTOS for deeply embedded systems. Apache-2.0 licensed. NuttX 9.0 (September 2026) added RISC-V 64, x86_64, and ELF64 support . POSIX-compliant with a focus on standards compliance .https://img.shields.io/github/stars/apache/nuttx?style=social&color=white~3,500RT-Thread — Chinese open-source RTOS with IoT focus. Apache-2.0 licensed. v5.3.0 (September 2026) added Rust language support, device-tree-based device models, DVFS (dynamic voltage and frequency scaling), and VirtIO 1.2 .https://img.shields.io/github/stars/RT-Thread/rt-thread?style=social&color=white~9,000Mbed OS — Arm's IoT OS (EOL July 2026). Apache-2.0 licensed. Remains publicly available but no longer actively maintained or supported by Arm . Mbed CE is the community-driven continuation.https://img.shields.io/github/stars/ARMmbed/mbed-os?style=social&color=white~3,000Ariel OS — New Rust-based RTOS for IoT microcontrollers. Dual Apache 2.0 / MIT license . Written fully in Rust with support for Arm Cortex-M and ESP32 architectures . Provides memory safety and modern tooling for embedded development .https://img.shields.io/github/stars/ariel-os/ariel-os?style=social&color=white~500Tenok — Linux-like RTOS for robotics and IoT. Open source . Designed for robotic applications and IoT with a Linux-like architecture . Prioritizes real-time performance and modularity .https://img.shields.io/github/stars/shengwen-tw/tenok?style=social&color=white~200Additional open-source options worth exploring:RepoDescriptionYocto Project — The de-facto standard for building custom Embedded Linux distributions. Flexible layer system for hardware support and customization .Buildroot — Simpler alternative to Yocto for building embedded Linux systems from scratch. Easy-to-use cross-compilation toolchain .OpenWrt — Linux distribution for embedded devices, primarily routers and gateways. Extensive package repository .Zephyr LTS — Long-term support releases of Zephyr RTOS for production deployments.FreeRTOS LTS — Long-term support libraries with security updates for two years .🤝 How to ContributeFork the repo.Add/edit entries in README.md (follow existing format).Include: name, link, 1–2 sentence description, and whether it's commercial or open-source.Submit PR with a short explanation.Star the repo if you find it useful!⚠️ DisclaimerThis is a community-curated list — not exhaustive and not an endorsement.IoT operating systems handle safety-critical and security-sensitive systems; certification requirements (IEC 61508, ISO 26262, DO-178C) must be independently verified before deployment.Critical lifecycle notices: Arm sunsetted Mbed OS in July 2026 — no longer actively maintained. The Mbed OS Community Edition (Mbed CE) fork is under active development and recommended for continued use . Microsoft announced Azure Sphere retirement with end-of-service set for September 2027. Existing deployments will continue to receive security updates through the retirement date, but new commitments are not commercially supported and migration planning should be in flight by mid-2026 .Open-source reality: The open-source ecosystem for IoT operating systems is exceptionally mature and production-proven. FreeRTOS has been downloaded every 175 seconds and is actively maintained by AWS with LTS releases . Zephyr RTOS reached version 4.1 with experimental Rust support and a modular architecture backed by the Linux Foundation . RIOT OS powers low-end embedded devices with a microkernel architecture and 5,535 stars . Contiki-NG continues the legacy of the original Contiki OS with a 3-clause BSD license . However, commercial platforms (Azure Sphere, VxWorks) provide certified safety packages, managed security services, and dedicated support that open-source alternatives may lack for the most demanding safety-critical applications. The open-source path is genuinely viable for IoT, industrial, and many safety-critical deployments.Made for embedded engineers, firmware developers, IoT architects, and real-time systems specialists.Let's make IoT operating systems more open, transparent, and accessible.
