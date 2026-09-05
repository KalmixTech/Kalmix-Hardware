<p align="center">
  <img src="Assets/KALMIX-Logo.png" alt="Kalmix" width="260">
</p>

<h3 align="center">Hardware Documentation Repository</h3>

<p align="center">
  Technical specifications, mechanical drawings, interface schematics, compliance documents,<br>
  and protocol references for the Kalmix GNSS product line.
</p>

<p align="center">
  <a href="https://www.kalmixtech.com">Website</a> ·
  <a href="https://www.kalmixtech.com/pages/documentation">Documentation</a> ·
  <a href="https://github.com/KalmixTech/Kalmix-Toolkit">Developer Toolkit</a>
</p>

---

## Product Index

| Product | Product Page | Datasheet | Interface | Mechanical | Protocol | Compliance |
|---|---|---|---|---|---|---|
| **SCOUT PRO** | [View Product](https://www.kalmixtech.com/products/kalmix-scout-pro) | [Datasheet](SCOUT-PRO/Datasheet/) | [Interface](SCOUT-PRO/Interface/) | [Mechanical](SCOUT-PRO/Mechanical/) | [Protocol](SCOUT-PRO/Protocol/) | [Compliance](SCOUT-PRO/Compliance/) |
| **SCOUT** | [View Product](https://www.kalmixtech.com/products/kalmix-scout) | [Datasheet](SCOUT/Datasheet/) | [Interface](SCOUT/Interface/) | [Mechanical](SCOUT/Mechanical/) | [Protocol](SCOUT/Protocol/) | [Compliance](SCOUT/Compliance/) |
| **GUIDE K35** | [View Product](https://www.kalmixtech.com/products/kalmix-guide-k35-gnss-module) | [Datasheet](GUIDE/Datasheet/) | [Interface](GUIDE/Interface/) | [Mechanical](GUIDE/Mechanical/) | [Protocol](GUIDE/Protocol/) | [Compliance](GUIDE/Compliance/) |

---

## Repository Structure

Each product has its own top-level folder. Documents are organized into the following standard categories:

| Folder | Contents |
|---|---|
| **Compliance** | Regulatory declarations such as FCC SDoC, NDAA statements, CE documents, and other product compliance files |
| **Datasheet** | Product-level specifications, performance data, ordering information, and electrical characteristics |
| **Interface** | Electrical interface specifications, pinout diagrams, connector definitions, and reference schematics |
| **Mechanical** | Dimensional drawings, tolerances, mounting information, material notes, and 3D CAD models |
| **Protocol** | Proprietary command references, communication notes, and product-specific protocol documentation |

```text
Kalmix-Hardware/
│
├── SCOUT-PRO/
│   ├── Compliance/
│   ├── Datasheet/
│   ├── Interface/
│   ├── Mechanical/
│   └── Protocol/
│
├── SCOUT/
│   ├── Compliance/
│   ├── Datasheet/
│   ├── Interface/
│   ├── Mechanical/
│   └── Protocol/
│
├── GUIDE/
│   ├── Compliance/
│   ├── Datasheet/
│   ├── Interface/
│   ├── Mechanical/
│   └── Protocol/
│
├── Assets/
│   └── KALMIX-Logo.png
└── README.md
