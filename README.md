# Hi, I'm Adam 👋

**Senior Customer Engineer @ Microsoft · Azure Networking Specialist** 

I'm a Senior Customer Engineer at Microsoft focused mostly on **Azure networking** — helping enterprises design hub-and-spoke, Virtual WAN, ExpressRoute, hybrid connectivity, and SD-WAN integrations. This profile is a curated index of the **hands-on labs**, **architecture articles**, and **troubleshooting toolkits** I've built while working with customers. Most content is reproducible end-to-end so you can deploy, break, and learn from real Azure topologies.

🔭 **Currently exploring:** AVNM Part Two · ExpressRoute monitoring · vWAN routing intent with forced tunneling
💬 **Ask me about:** vWAN custom routing · ExR Fastpath · ARS dual-home · BGP-over-IPsec · NAT Gateway

📣 **Connect:** [LinkedIn](https://www.linkedin.com/in/at-10993764/) · [GitHub](https://github.com/adtork) · [MS Tech Community](https://techcommunity.microsoft.com/) · [Azure Networking Docs](https://learn.microsoft.com/azure/networking/)

## 📋 Table of Contents
- [Labs](#-labs)
- [Architectures](#-architectures)
- [Articles — ExpressRoute & Virtual WAN](#-expressroute--virtual-wan)
- [Articles — Networking Fundamentals](#-networking-fundamentals)
- [Tools & Snippets](#-tools--snippets)
- [Tech Stack](#-tech-stack)

## 🧪 Labs
- [BGP over IPSec · Blue -Yellow Isolation](https://github.com/adtork/Lab-Virtual-Wan-Custom-Routing-BGP-over-IPSEC) — Custom vHub routing with Cisco CSR branch over IPsec + BGP, with `rt_yellow` / `rt_blue` route table isolation
- [Azure Virtual Network Manager](https://github.com/adtork/Lab-Azure-Virtual-Network-Manager) — Walk-throughs for Mesh, Hub-and-Spoke, and Hub-and-Spoke + Global Mesh
- [AVNM Part Two](https://github.com/adtork/AVNM-Part-Two) — Advanced AVNM scenarios *(work in progress)*
- [Route Server Dual Home](https://github.com/adtork/Azure-Route-Server-Dual-Home) — Highly available ARS across two hubs with BGP + VNet-to-VNet IPsec
- [Dual vWAN Secure Hubs + BGP-over-IPsec](https://github.com/adtork/dual-vwan-secure-hubs-bgp-over-ipsec) — Dual-region secured vWAN hubs with Private Routing Intent and full bow-tie BGP-over-IPsec branches using Strongwan (Bicep / Terraform / CLI / PowerShell)
- [ILB With Apache Server via Vnet Peering](https://github.com/adtork/ILB-with-Apache-Server) -Client connection over Vnet peering to an ILB with two Apache Servers in the BE. NatGW provided soley for deployment of Apache Server

## 🏛️ Architectures
- [AVNM vs Hub & Spoke vs Virtual WAN](https://github.com/adtork/azure-network-topology-comparison) — Side-by-side comparison, decision tree, cost breakdown, and a hybrid AVNM + Hub & Spoke reference architecture

## ⚡ Hybrid Connectivity
- [ExR Fastpath](https://github.com/adtork/ExpressRoute-Fastpath) — When to use Fastpath and exactly what it bypasses
- [MSEE Hairpin Design Alternatives](https://github.com/adtork/MSEE-Hairpin-Design-Considerations) — How to avoid the classic MSEE hairpin
- [vWAN-to-vWAN Connection Options](https://github.com/adtork/vWAN-to-vWAN-Connection-Options) — Patterns for connecting multiple vWANs
- [vWAN with ExR Bow-Tie + HRP](https://github.com/adtork/vWAN-Dual-Hubs-with-ExR-Bow-Tie) — Dual-hub bow-tie with high-redundancy paths
- [vWAN Routing Intent + Forced Tunneling](https://github.com/adtork/vWAN-Routing-Intent-with-Forced-Tunneling) — Securing internet egress with routing intent
- [What is this ExR IP?](https://github.com/adtork/ExpressRoute--What-is-this-IP-) — Demystifying the IPs you see on ExR resources
- [vWAN Traffic Flow Patterns](https://github.com/adtork/vWAN-Traffic-Flow-Scenarios) — Common end-to-end traffic flows through vWAN
- [vWAN Routing Limits & Mitigations](https://github.com/adtork/vwan-routing-limits) — Contention-point map of route limits across ER, S2S BGP, SD-WAN NVA, and VNet peering — with mitigation playbook
- [Migrating off IPsec-over-ExpressRoute to ER-only](https://github.com/adtork/ipsec-over-er-to-er-only) — Why the IPsec overlay is the throughput chokepoint, what ER-only + FastPath buys you, and a 4-step cutover plan
- [ExR Monitoring & Best Practices](https://github.com/adtork/ExpressRoute-Monitoring) — Field guide for ExpressRoute monitoring, alerting, and HA/DR design (BFD, dual MSEEs, two POPs, bow-tie, FastPath)

## 🌐 Networking Fundamentals
- [Network Perf in Azure](https://github.com/adtork/Azure-Networking-Performance) — Throughput, latency, and tuning levers
- [Azure IP Addressing & SNAT](https://github.com/adtork/Azure-IP-Addressing-and-SNAT) — Subnet sizing, pseudo-VIP, and the 3 SNAT options
- [Empty VNet Trick](https://github.com/adtork/Empty-Vnet-Trick) — Advertising indirect spoke routes to on-prem

## 🔧 Tools & Snippets
- [Simple Loop Scripts](https://github.com/adtork/Simple-Loop-Scripts) — NetCat / Curl / Wget / Test-NetConnection / PSPing loop scripts for connectivity troubleshooting
- [ARG Kusto Queries](https://github.com/adtork/ARG-Kusto-Queries) — A growing catalog of KQL queries for Azure Resource Graph inventory

## 🛠️ Tech Stack
![Azure](https://img.shields.io/badge/-Azure-0078D4?logo=microsoftazure&logoColor=white) ![Bicep](https://img.shields.io/badge/-Bicep-0089D6?logo=microsoftazure&logoColor=white) ![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?logo=terraform&logoColor=white) ![Cisco](https://img.shields.io/badge/-Cisco-1BA0D7?logo=cisco&logoColor=white) ![Bash](https://img.shields.io/badge/-Bash-4EAA25?logo=gnu-bash&logoColor=white) ![PowerShell](https://img.shields.io/badge/-PowerShell-5391FE?logo=powershell&logoColor=white) ![KQL](https://img.shields.io/badge/-KQL-0078D4?logo=microsoft&logoColor=white) ![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white) ![VS Code](https://img.shields.io/badge/-VS%20Code-007ACC?logo=visualstudiocode&logoColor=white)

*Thanks for stopping by!* ✨
