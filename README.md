# 🌐 WAN Routing Protocols & NAT — Cisco Packet Tracer Lab

A multi-protocol WAN simulation built in **Cisco Packet Tracer**, designed to explore how EIGRP, OSPF, and BGP operate and interact within the same network infrastructure.

---

## 📌 About the Project

This lab simulates a realistic WAN environment where three independent routing domains coexist and exchange routing information through explicit redistribution at their boundaries. The design mirrors how real-world ISP and enterprise networks are structured, with internal routing protocols managing intra-domain traffic and BGP handling inter-domain connectivity.

NAT/PAT is configured at both network edges to connect private LAN segments to the WAN.

The full technical documentation — including configuration details, protocol analysis, verification outputs, and troubleshooting — is available in the `WAN_Routing_Lab.docx` file included in this repository.

---

## 🧩 What's Included

| Component | Details |
|-----------|---------|
| Routing Protocols | EIGRP, OSPF (Area 0), eBGP |
| Route Redistribution | EIGRP ↔ OSPF ↔ BGP (bidirectional) |
| NAT | PAT (NAT Overload) on both edge routers |
| LAN Segmentation | VLANs with inter-VLAN routing via sub-interfaces |
| Routers | 12 core + 4 transit + 2 NAT edge |

---

## 🚀 Getting Started

The **`.pkt` Packet Tracer file is included in this repository** — open it directly to explore the full topology, inspect every router's configuration, and practice hands-on in a fully operational network environment.

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git

# Then open wan_routing_lab.pkt in Cisco Packet Tracer
```

This is an ideal sandbox for experimenting with routing protocol behavior, redistribution policies, and NAT — without any risk to a real network.

---

## 📁 Repository Structure

```
📦 CPT_Routing-Environment/
├── 📄 README.md
├── 🖼️ CPT_Routing-Environment-IMG.png   ← Network topology diagram
├── 📄 Report: WAN - RoutingProtocols & NAT.pdf   ← Full technical documentation
└── 📡 WAN_Routing_Environment.pkt   ← Cisco Packet Tracer project file
```
