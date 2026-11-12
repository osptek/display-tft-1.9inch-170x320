<p align="left"><img alt="OSPTEK" src="../../images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 1.9″ TFT Display 170×320 (YDP190HT002-V9)</h1>

<p align="center"><b>TFT module · MCU/QSPI · ST7789</b></p>

<p align="center"><a href="./README.md">简体中文</a> | English · <a href="../../README_EN.md">Family index</a></p>

<p align="center">
  <img alt="Interface: MCU/QSPI" src="https://img.shields.io/badge/Interface-MCU%20%C2%B7%20QSPI-27AE60?style=flat-square" />
  <img alt="Driver: ST7789" src="https://img.shields.io/badge/Driver-ST7789-E7352C?style=flat-square" />
  <img alt="Touch: CST816D" src="https://img.shields.io/badge/Touch-CST816D-F39C12?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 1.9&quot; 170×320 TFT module product image" src="./images/product.png" width="640" /></p>

## Contents

- [Specifications](#specifications)
- [Resources](#resources)
- [Repository layout](#repository-layout)
- [Buy](#buy)
- [Support](#support)

---

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 1.9 inch |
| Type | TFT |
| Resolution | 170×320 |
| Outline | 30.00 x 65.00 x 3.51 mm |
| Active area | 22.7 x 42.72 mm |
| Interface | MCU/QSPI |
| Driver IC | ST7789 |
| Touch IC | CST816D |

> Full outline, FPC definition, power, and timing follow the product datasheet / driver IC datasheet.

## Resources

| Category | File |
| ---- | ---- |
| Datasheet | [`ST7789V3_SPEC_Preliminary_V0.0_200102.pdf`](./datasheets/ST7789V3_SPEC_Preliminary_V0.0_200102.pdf) |
| Datasheet | [`YDP190HT002-V9.pdf`](./datasheets/YDP190HT002-V9.pdf) |
| CAD file | [`YDP190HT002-V9_外形图.pdf`](./cad/YDP190HT002-V9_%E5%A4%96%E5%BD%A2%E5%9B%BE.pdf) |
| Init code | [`ST7789_HSD1.9-2.2gamma-20230411.txt`](./code/ST7789_HSD1.9-2.2gamma-20230411.txt) |

## Repository layout

```text
display-tft-1.9inch-170x320/ # repo root (nav: ../../README_EN.md; sample projects under root examples/)
└── versions/
    └── YDP190HT002-V9/        # full materials for this part number
        ├── README.md
        ├── README_EN.md
        ├── osptek.yml
        ├── images/
        ├── datasheets/       # product datasheet + driver/touch IC datasheets
        ├── cad/              # outline/cover CAD
        └── code/             # init reference code
```

## Buy

See the [repo home page](../../README_EN.md#where-to-buy).

## Support

See the [repo home page](../../README_EN.md#support).

---

<p align="center"><sub>© 2026 OSPTEK · Materials in this repository are licensed under CC BY 4.0</sub></p>
