# Awesome-Virtual-Desktop-Infrastructure-VDI

## Top Virtual Desktop Infrastructure (VDI) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Remote Desktops, Browser-Based Workspaces, DaaS, Session Hosts & Secure Application Delivery*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Virtual Desktop Infrastructure (VDI)**. These systems deliver full desktops or isolated app sessions to users over the network—on-prem, hybrid, or as Desktop-as-a-Service (DaaS).



**Examples** include Citrix Workspace, Windows 365, VMware Horizon, Amazon WorkSpaces, Microsoft Azure Virtual Desktop, Nutanix Frame, Parallels RAS, Kasm Workspaces, Shells, Paperspace, and **Kasm Workspaces** (`kasmtech`)—open-source web-native virtual desktop infrastructure.



**Open-source emphasis**: Full enterprise VDI is commercial-heavy, but strong open options exist: **Kasm**, **Apache Guacamole**, **IsardVDI**, **Ravada**, and **QVD**. This section lists every significant relevant project found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Citrix Workspace / DaaS, VMware Horizon, Parallels RAS](https://www.citrix.com/)**  

  Classic enterprise VDI and app virtualization—high protocol performance, HDX/Blast-class experience, and large ecosystem support.



- **[Windows 365, Azure Virtual Desktop, Amazon WorkSpaces](https://www.microsoft.com/en-us/windows-365)**  

  Cloud DaaS offerings—managed Windows desktops with identity and security integration into major clouds.



- **[Nutanix Frame, Kasm (commercial), Paperspace, Shells](https://www.nutanix.com/products/frame)**  

  Browser-first and GPU-capable desktop platforms for secure access and creative/workstation workloads.



- **[Other commercial VDI / DaaS platforms](https://aws.amazon.com/workspaces/)**  

  Additional remote desktop and secure browser services.



## Open-Source GitHub Projects



- **[Kasm Workspaces](https://github.com/kasmtech)**  

  Leading open-source web-native VDI—containerized desktops and browsers streamed to HTML5 clients; strong for secure browser isolation and disposable workspaces.



- **[KasmVNC](https://github.com/kasmtech/KasmVNC)**  

  Modern open VNC server/client stack used by Kasm—web-based, secure remote desktop streaming.



- **[Apache Guacamole](https://github.com/apache/guacamole-server)**  

  Clientless open remote desktop gateway—RDP, VNC, and SSH in the browser without a local agent install.



- **[IsardVDI](https://github.com/isard-vdi/isardvdi)**  

  Open VDI platform focused on education and labs—create, template, and deliver virtual desktops at scale.



- **[Ravada VDI](https://github.com/UPC/ravada)**  

  Open virtual desktop manager—KVM-based desktops with a web UI for teaching and multi-user environments.



- **[QVD (Quality Virtual Desktop)](https://github.com/theqvd)**  

  Open Linux VDI solution—efficient session delivery for Linux desktops and thin clients.



- **[noVNC](https://github.com/novnc/noVNC)**  

  Open VNC client web application—browser access to VNC sessions; building block for many VDI UIs.



- **[ThinLinc (community aspects) / other Linux session tools](https://github.com/search?q=VDI+OR+remote+desktop+open+source)**  

  Community and Linux-oriented remote desktop stacks complementary to full VDI platforms.



- **[Virtlyst / libvirt web UIs](https://github.com/search?q=libvirt+remote+desktop)**  

  Lightweight open management UIs that can front KVM desktops for smaller deployments.



### Additional Strong Open-Source Options



- **Browser-native secure workspaces**: Kasm Workspaces.

- **Protocol gateway (RDP/VNC/SSH)**: Apache Guacamole.

- **Education / lab VDI**: IsardVDI or Ravada.

- **Linux-centric VDI**: QVD.

- **Composable stacks**: KVM/libvirt → Guacamole or KasmVNC → identity (Keycloak) → HTML5 clients.

- Commercial VDI still leads for Windows multi-session scale, proprietary display protocols, and enterprise support matrices.



**Frameworks for building custom systems**:  

**Kasm** for containerized web VDI; **Guacamole** as a universal remote gateway; **IsardVDI/Ravada** for managed KVM desktop pools.  

Fully open VDI is practical for Linux, secure browsers, and labs; large Windows enterprise estates often remain on Citrix, AVD, or Horizon.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- VDI concentrates sensitive user sessions—harden brokers, enforce MFA/SSO, isolate networks, and monitor for session hijacking. Disposable container desktops reduce persistence risk but still need image hygiene.

- Open-source VDI offers control and cost efficiency. Commercial DaaS shifts capacity and Windows licensing complexity to the vendor. Neither replaces endpoint policy and data-loss prevention design.



---



**Made for EUC architects, security teams, and platform engineers delivering desktops as a service.**  

Let's expand open VDI and browser isolation while recognizing the Windows-scale depth that leading commercial virtual desktop platforms deliver.
