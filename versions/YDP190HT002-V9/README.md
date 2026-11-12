<p align="left"><img alt="OSPTEK" src="../../images/logo.png" width="200" /></p>

<h1 align="center">OSPTEK 1.9″ TFT 显示屏 170×320（YDP190HT002-V9）</h1>

<p align="center"><b>TFT 模组 · MCU/QSPI · ST7789</b></p>

<p align="center"><a href="./README_EN.md">English</a> | 简体中文 · <a href="../../README.md">规格族索引</a></p>

<p align="center">
  <img alt="Interface: MCU/QSPI" src="https://img.shields.io/badge/Interface-MCU%20%C2%B7%20QSPI-27AE60?style=flat-square" />
  <img alt="Driver: ST7789" src="https://img.shields.io/badge/Driver-ST7789-E7352C?style=flat-square" />
  <img alt="Touch: CST816D" src="https://img.shields.io/badge/Touch-CST816D-F39C12?style=flat-square" />
</p>

<p align="center"><img alt="OSPTEK 1.9 寸 170×320 TFT 模组宣传图" src="./images/product.png" width="640" /></p>

## 目录

- [规格参数](#规格参数)
- [相关资料](#相关资料)
- [仓库结构](#仓库结构)
- [购买链接](#购买链接)
- [技术支持](#技术支持)

---

## 规格参数

| 项目 | 规格 |
| ---- | ---- |
| 尺寸 | 1.9 英寸 |
| 类型 | TFT |
| 分辨率 | 170×320 |
| 外形尺寸 | 30.00 x 65.00 x 3.51 mm |
| 有效显示区域 | 22.7 x 42.72 mm |
| 接口 | MCU/QSPI |
| 驱动 IC | ST7789 |
| 触摸驱动 | CST816D |

> 完整外形尺寸、FPC 定义、供电与时序以产品规格书 / 驱动手册为准。

## 相关资料

| 分类 | 文件 |
| ---- | ---- |
| 规格文档 | [`ST7789V3_SPEC_Preliminary_V0.0_200102.pdf`](./datasheets/ST7789V3_SPEC_Preliminary_V0.0_200102.pdf) |
| 规格文档 | [`YDP190HT002-V9.pdf`](./datasheets/YDP190HT002-V9.pdf) |
| CAD 图纸 | [`YDP190HT002-V9_外形图.pdf`](./cad/YDP190HT002-V9_%E5%A4%96%E5%BD%A2%E5%9B%BE.pdf) |
| 初始化代码 | [`ST7789_HSD1.9-2.2gamma-20230411.txt`](./code/ST7789_HSD1.9-2.2gamma-20230411.txt) |

## 仓库结构

```text
display-tft-1.9inch-170x320/ # 仓库根（导航见 ../../README.md，示例工程见根目录 examples/）
└── versions/
    └── YDP190HT002-V9/        # 本料号完整资料
        ├── README.md
        ├── README_EN.md
        ├── osptek.yml
        ├── images/
        ├── datasheets/       # 产品规格书 + 驱动/触摸 IC 数据手册
        ├── cad/              # 外形/盖板 CAD
        └── code/             # 初始化参考代码
```

## 购买链接

见[仓库首页](../../README.md#购买链接)。

## 技术支持

见[仓库首页](../../README.md#技术支持)。

---

<p align="center"><sub>© 2026 OSPTEK 鱼鹰光电 · 本仓库资料采用 CC BY 4.0 许可</sub></p>
