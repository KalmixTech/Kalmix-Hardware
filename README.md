<p align="center">
  <img src="Assets/kalmix-logo.png" alt="Kalmix" width="260">
</p>

<h3 align="center">Hardware Documentation Repository</h3>

<p align="center">
  Technical specifications, mechanical drawings, interface schematics, compliance certificates,<br>and protocol references for the Kalmix product line.
</p>

<p align="center">
  <a href="https://www.kalmixtech.com">Website</a> · <a href="https://www.kalmixtech.com/blogs/doc-scout-pro/scout-pro-product-overview">SCOUT PRO</a> · <a href="https://www.kalmixtech.com/blogs/doc-sout/scout-product-overview">SCOUT</a>
</p>

---

## Repository Structure

Each product has its own top-level folder. Documents are organized into the following standard categories:

| Folder | Contents |
|--------|----------|
| **Compliance** | Regulatory declarations (FCC SDoC, NDAA, CE, etc.) |
| **Datasheet** | Product-level specifications and performance data |
| **Interface** | Electrical interface specification and reference schematics |
| **Mechanical** | Dimensional drawings, tolerances, materials, 3D CAD models (.STEP) |
| **Protocol** | Proprietary command / protocol reference |

```
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
├── assets/
│   └── kalmix-logo.png
└── README.md
```

> New product lines (antennas, receivers, modules, etc.) follow the same folder convention. Not every product requires all five categories — include only what applies.

## 3D CAD Models

`.STEP` files in `Mechanical/` folders are 1:1 scale (millimeters, ISO 10303). Compatible with SolidWorks, Fusion 360, AutoCAD, and other standard CAD tools.

## License

All documents in this repository are proprietary to **Shanghai IOTARS Co., Ltd.** and provided for hardware integration purposes only. Redistribution requires written permission.

---

<p align="center">
  <sub>Shanghai IOTARS Co., Ltd. · <a href="https://www.kalmixtech.com">kalmixtech.com</a></sub>
</p>
