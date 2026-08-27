<p align="left"><img alt="OSPTEK" src="./images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 3.95″ TFT 480×480 (ST7102 · RGB)</h1>

<p align="center"><b>Square TFT module · RGB · ST7102 · In-Cell touch</b></p>

<p align="center"><a href="./README.md">简体中文</a> | English · <a href="../../README_EN.md">Family index</a></p>

<p align="center">
  <img alt="Size: 3.95 inch" src="https://img.shields.io/badge/Size-3.95%22-3498DB?style=flat-square" />
  <img alt="Resolution: 480x480" src="https://img.shields.io/badge/Resolution-480%C3%97480-8E44AD?style=flat-square" />
  <img alt="Interface: RGB" src="https://img.shields.io/badge/Interface-RGB-27AE60?style=flat-square" />
  <img alt="Driver: ST7102" src="https://img.shields.io/badge/Driver-ST7102-E7352C?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 3.95&quot; 480×480 TFT RGB module (ST7102) product image" src="./images/product.png" width="640" /></p>

## Contents

- [Overview](#overview)
- [Specifications](#specifications)
- [Repository layout](#repository-layout)
- [Resources](#resources)
- [Buy](#buy)
- [Support](#support)

---

## Overview

OSPTEK **3.95″ 480×480 TFT** is a **RGB 18-bit** color display module driven by **ST7102**, with **In-Cell** capacitive touch (`TP_SDA` / `TP_SCL` on the FPC). Suited to square HMI, instruments, and mid-size panels.

Spec ID (repository name): `3.95-tft-480x480-rgb-st7102`

Current module version: **YDP395B005-V4**. Electrical and mechanical details follow [`docs/YDP395B005-V4.pdf`](./docs/YDP395B005-V4.pdf).

## Specifications

| Item | Spec |
| ---- | ---- |
| Size | 3.95 inch |
| Type | TFT / IPS (color · In-Cell) |
| Resolution | 480×480 |
| Interface | RGB 18-bit |
| Driver IC | ST7102 |
| Touch | In-Cell (capacitive; TP I²C on FPC) |

> Full outline, FPC definition, power, and timing follow the product datasheet / driver IC datasheet.

## Repository layout

```text
3.95-tft-480x480-rgb-st7102/                                # repo root (nav: ../../README_EN.md)
└── versions/
    └── YDP395B005-V4/                                # full materials for this part number
        ├── README.md
        ├── README_EN.md
        ├── images/
        └── docs/
```

## Resources

### Product files

| Resource | Link |
| ---- | ---- |
| Product datasheet (YDP395B005-V4) | [`docs/YDP395B005-V4.pdf`](./docs/YDP395B005-V4.pdf) |
| Driver IC datasheet (ST7102) | [`docs/ST7102_Datasheet_V0.22.pdf`](./docs/ST7102_Datasheet_V0.22.pdf) |
| Init sequence (text) | [`docs/CODE.txt`](./docs/CODE.txt) |

## Buy

<p align="center">
  <a href="https://www.aliexpress.com/store/1105701619"><img alt="AliExpress store" src="https://img.shields.io/badge/AliExpress-Official_Store-FF6A00?style=for-the-badge" /></a>
  &nbsp;&nbsp;
  <a href="https://shop110742373.taobao.com/"><img alt="Taobao store" src="https://img.shields.io/badge/Taobao-Official_Store-FF6A00?style=for-the-badge" /></a>
</p>

**Overseas (AliExpress)**

- Store: [OSPTEK Official Store](https://www.aliexpress.com/store/1105701619)

**China (Taobao)**

- Store: [鱼鹰光电工厂店](https://shop110742373.taobao.com/)

## Support

- Technical support / product inquiry: <luyu@osptek.com>
- QQ group: **985881096**
- Website: <https://osptek.com/>
- Feel free to open an Issue in this repository if you have any questions

---

<p align="center"><sub>© 2026 OSPTEK · Materials in this repository are licensed under CC BY 4.0</sub></p>
