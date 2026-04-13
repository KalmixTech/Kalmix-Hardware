<p align="center">
  <img src="https://cdn.shopify.com/s/files/1/0804/7040/9458/files/kalmix-logo2-blue.png?v=1745584498" alt="Kalmix" width="260">
</p>

<h3 align="center">Hardware Documentation Repository</h3>

<p align="center">
  Technical specifications, mechanical drawings, interface schematics, and compliance certificates<br>for the Kalmix GNSS receiver product line.
</p>

<p align="center">
  <a href="https://www.kalmixtech.com">Website</a> · <a href="https://www.kalmixtech.com/blogs/doc-scout-pro/scout-pro-product-overview">SCOUT PRO Docs</a> · <a href="https://www.kalmixtech.com/blogs/doc-sout/scout-product-overview">SCOUT Docs</a>
</p>

---

## Products

| Product | Module | Chip | Key Differentiator | Online Docs |
|---------|--------|------|--------------------|-------------|
| **SCOUT PRO** | Kalmix™ GUIDE (K35 Series) | Airoha AG3335 | EPO™ / EASY™ / AIC, 135-ch | [Documentation →](https://www.kalmixtech.com/blogs/doc-scout-pro/scout-pro-product-overview) |
| **SCOUT** | Kalmix™ NOMAD (K16 Series) | Beken BK1662 | 200-ch, up to 20 Hz fix rate | [Documentation →](https://www.kalmixtech.com/blogs/doc-sout/scout-product-overview) |

Both products share the same ruggedized IP67 housing (67 × 67 × 22.2 mm) with integrated dual-band L1/L5 antenna, USB Type-C interface, and plug-and-play USB 2.0 connectivity via CH340N bridge.

---

## Repository Structure

```
Kalmix-Hardware/
│
├── SCOUT-PRO/
│   ├── Compliance/
│   │   ├── FCC Supplier's Declaration of Conformity-SCOUT PRO.pdf
│   │   └── NDAA Compliance Statement-SCOUT PRO.pdf
│   ├── Datasheet/
│   │   └── SCOUT PRO Datasheet.pdf
│   ├── Interface/
│   │   ├── SCOUT PRO Interface Specification.pdf
│   │   └── SCOUT PRO Interface Reference Schematic.png
│   ├── Mechanical/
│   │   ├── SCOUT PRO Mechanical Specification.pdf
│   │   └── SCOUT PRO.STEP
│   └── Protocol/
│       └── SCOUT PRO Protocol Reference.pdf
│
├── SCOUT/
│   ├── Compliance/
│   │   ├── FCC Supplier's Declaration of Conformity-SCOUT.pdf
│   │   └── NDAA Compliance Statement-SCOUT.pdf
│   ├── Datasheet/
│   │   └── SCOUT Datasheet.pdf
│   ├── Interface/
│   │   ├── SCOUT Interface Specification.pdf
│   │   └── SCOUT Interface Reference Schematic.png
│   ├── Mechanical/
│   │   ├── SCOUT Mechanical Specification.pdf
│   │   └── SCOUT.STEP
│   └── Protocol/
│       └── SCOUT Protocol Reference.pdf
│
└── README.md
```

## Document Guide

| Folder | Contents | Description |
|--------|----------|-------------|
| **Compliance** | FCC SDoC, NDAA Statement | Regulatory declarations for US market distribution |
| **Datasheet** | Product Datasheet | GNSS performance, constellation support, electrical & environmental specs |
| **Interface** | Interface Specification, Schematic | USB Type-C pinout, connection architecture, reference circuit diagram |
| **Mechanical** | Mechanical Specification, 3D CAD (.STEP) | Enclosure dimensions, tolerances, materials, 2D drawing, 1:1 STEP model |
| **Protocol** | Protocol Reference | Proprietary command set — PAIR commands (SCOUT PRO) / POLCFG commands (SCOUT) |

## Quick Specs Comparison

| Parameter | SCOUT PRO | SCOUT |
|-----------|-----------|-------|
| Channels | 135 | 200 |
| Constellations | GPS, GLO, GAL, BDS, QZSS, SBAS | GPS, GLO, GAL, BDS, QZSS, SBAS |
| BDS Bands | B1I, B1C, B2a | B1I, B1C, B2a, B2I |
| RTK Velocity Accuracy | 0.03 m/s | 0.01 m/s |
| Max Fix Rate | 10 Hz | 20 Hz |
| TTFF (Cold) | 26 s (std) / 5 s (EPO™) | 28 s |
| IMU (DR variant) | ST LSM6DSR | Bosch BMI325 |
| Command Protocol | PAIR (NMEA-style w/ checksum) | POLCFG (plaintext, $OK/$FAIL) |
| Housing | 67 × 67 × 22.2 mm, IP67 | Same |
| Interface | USB Type-C, USB 2.0, 115200 bps default | Same |

## Using the 3D CAD Models

The `.STEP` files in each `Mechanical/` folder are 1:1 scale models (millimeters). Import directly into SolidWorks, Fusion 360, AutoCAD, or any ISO 10303-compatible CAD tool for custom bracket design, enclosure integration, or 3D printing.

## License

All documents in this repository are proprietary to **Shanghai IOTARS Co., Ltd.** and provided for hardware integration purposes only. Redistribution requires written permission.

---

<p align="center">
  <sub>Shanghai IOTARS Co., Ltd. · <a href="https://www.kalmixtech.com">kalmixtech.com</a></sub>
</p>
