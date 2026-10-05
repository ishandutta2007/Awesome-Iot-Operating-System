# Awesome-Iot-Operating-System

# Awesome-Iot-Operating-System

## Top IoT Operating System Platforms Ecosystem

**Curated List of Commercial Platforms & Open-Source GitHub Projects**

*Focused on Real-Time Operating Systems (RTOS), Embedded Linux, Constrained-Device OS, Secure IoT Kernels & Connected-Device Foundations*

**Last updated: October 2026**



This repository tracks notable **commercial / managed platforms** and **open-source projects** for **IoT Operating Systems**. These systems provide the foundational software layer for microcontrollers, gateways, and connected devices—handling scheduling, networking, power management, security, and hardware abstraction in resource-constrained environments.



**Examples** include Azure Sphere OS, FreeRTOS, Zephyr RTOS, ARM Mbed OS, TinyOS, Contiki, RIOT OS, Amazon FreeRTOS, Embedded Linux, and VxWorks (the category leaders and widely used options).



**Open-source emphasis**: The IoT OS landscape is unusually rich in high-quality open-source projects. **Zephyr**, **FreeRTOS**, **RIOT OS**, **Contiki-NG**, **Mbed OS**, **TinyOS**, **NuttX**, and various Embedded Linux distributions dominate constrained and mid-range devices. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Azure Sphere OS](https://azure.microsoft.com/products/azure-sphere/)**  

  Microsoft’s secured, Linux-based OS and cloud service tightly coupled with Azure Sphere certified silicon for end-to-end device security, certificate management, and managed over-the-air updates.



- **[Amazon FreeRTOS (AWS IoT integrations)](https://aws.amazon.com/freertos/)**  

  AWS-supported libraries and distribution built on FreeRTOS, optimized for secure connectivity to AWS IoT Core and related services (the core kernel remains open-source).



- **[VxWorks](https://www.windriver.com/products/vxworks)**  

  Commercial real-time operating system from Wind River, widely used in safety-critical, industrial, aerospace, automotive, and high-reliability embedded systems.



- **[ARM Mbed OS (commercial support / ecosystem)](https://os.mbed.com/)**  

  While the core is open-source, Arm and partners provide commercial tooling, certified platforms, and long-term support around Mbed OS.



- **[Embedded Linux commercial distributions](https://www.windriver.com/)**  

  Vendor-supported Embedded Linux offerings (Wind River Linux, commercial Yocto-based distributions, and similar) for gateways and higher-capability IoT devices.



- **[Azure RTOS / Eclipse ThreadX lineage](https://azure.microsoft.com/products/rtos/)**  

  High-performance RTOS with commercial heritage (formerly ThreadX), now available under open terms via the Eclipse Foundation, with Microsoft Azure IoT integrations.



- **[Other vendor RTOS with managed services](https://www.windriver.com/)**  

  Proprietary or dual-licensed RTOS offerings that include long-term support, certification artifacts (IEC 61508, DO-178C, etc.), and cloud management hooks.



- **[Secure element + OS bundles](https://azure.microsoft.com/products/azure-sphere/)**  

  Hardware-software packages (such as Azure Sphere) that combine certified silicon with a locked-down OS and cloud backend for high-security IoT deployments.



- **[Industrial and safety-certified commercial RTOS](https://www.windriver.com/products/vxworks)**  

  Platforms offering formal safety and security certifications that many pure open-source projects do not provide out of the box.



- **[Managed device OS services](https://azure.microsoft.com/)**  

  Cloud-tied OS management planes that handle certificate lifecycle, OTA updates, and fleet security for specific silicon platforms.



## Open-Source GitHub Projects

- **[Zephyr RTOS](https://github.com/zephyrproject-rtos/zephyr)**  

  Scalable, secure, open-source RTOS (Linux Foundation) supporting multiple architectures, rich networking stacks, power management, and a large ecosystem of boards and drivers.



- **[FreeRTOS](https://github.com/FreeRTOS/FreeRTOS)**  

  The most widely used open-source real-time operating system for microcontrollers—small footprint, highly portable, and backed by a large community and Amazon.



- **[RIOT OS](https://github.com/RIOT-OS/RIOT)**  

  Friendly open-source OS for the IoT designed for low-power, resource-constrained devices with a uniform API, real-time capabilities, and strong networking support.



- **[Contiki-NG](https://github.com/contiki-ng/contiki-ng)**  

  Next-generation Contiki—open-source OS focused on low-power IPv6 networking, 6LoWPAN, RPL, and constrained wireless sensor networks.



- **[Mbed OS](https://github.com/ARMmbed/mbed-os)**  

  Open-source embedded operating system from Arm, optimized for Cortex-M microcontrollers with connectivity, security, and RTOS features.



- **[TinyOS](https://github.com/tinyos/tinyos-main)**  

  Classic open-source OS designed for wireless sensor networks and extremely resource-constrained devices.



- **[Apache NuttX](https://github.com/apache/nuttx)**  

  Mature, POSIX-compliant open-source RTOS suitable for a wide range of embedded and IoT applications.



- **[Embedded Linux (Yocto Project / OpenEmbedded)](https://github.com/yoctoproject)**  

  The foundation for building custom, production-grade Linux distributions for IoT gateways and higher-end devices.



- **[OpenWrt](https://github.com/openwrt/openwrt)**  

  Open-source Linux distribution widely used for routers, gateways, and network-centric IoT devices.



- **[Documentation and Zephyr / FreeRTOS / RIOT playbooks](https://docs.zephyrproject.org/)**  

  Resources for getting started, board support packages, networking stacks, security features, and production deployment of open IoT operating systems.



### Additional Strong Open-Source Options

- Choosing **Zephyr** for a modern, modular, vendor-neutral RTOS with excellent connectivity and security features.

- Using **FreeRTOS** when a minimal, battle-tested kernel and broad silicon support are the priority.

- Adopting **RIOT OS** or **Contiki-NG** for low-power, standards-based wireless sensor and mesh networks.

- Building custom images with the **Yocto Project** or **OpenWrt** for Linux-class IoT gateways.

- Exploring **NuttX** for POSIX-like behavior on constrained hardware.

- Accepting that certain commercial offerings (Azure Sphere’s hardware-rooted security model, VxWorks safety certifications, long-term vendor support contracts) still fill specialized enterprise and regulated needs.

- Focusing open-source efforts on portability, community-driven drivers, security hardening, and freedom from proprietary lock-in.



**Frameworks for building custom systems**: Select Zephyr or FreeRTOS for MCU nodes → add networking and security subsystems → use Yocto/OpenWrt for gateways → manage fleets with open or cloud tools. Suitable for the vast majority of new IoT products. Safety-critical or highly regulated domains may still require commercial certified RTOS options.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's commercial/managed or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- IoT operating systems run on resource-constrained and often safety- or security-sensitive devices. Choice of OS, board support, and update strategy must match product requirements. This list is not engineering or certification advice.



---

**Made for embedded engineers, IoT architects, and open-source hardware advocates.**

Let's keep connected devices efficient, secure, and as open as practical.
