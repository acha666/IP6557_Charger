# IP6557 Charger

[Chinese Document / 中文文档](./readme-zh.md) | English Document

*A fast-charging module based on the Injoinic IP6557 buck-boost SoC*  

![PCB Photo 1](docs/images/board-ce5fdf7-1.jpg) ![PCB Photo 2](docs/images/board-ce5fdf7-2.jpg)

## Project Status

- [x] Schematic design  
- [x] PCB layout  
- [x] PCB fabrication  
- [x] PCB validation  

## Device Overview

- **[IP6557-C]()** – An SoC that integrates a buck-boost controller and USB-C fast-charging protocols  
- **[NTTFS5C673NL](https://www.onsemi.com/download/data-sheet/pdf/nttfs5c673nl-d.pdf) MOSFET** –  
  $`V_{DS}=60\,\text{V},\;R_{DS(\mathrm{on})}=11\,\text{m}\Omega,\;C_{\mathrm{iss}}=880\,\text{pF},\;Q_{g(\mathrm{th})}=1.0\,\text{nC}\;@\,4.5\,\text{V}`$

## Key PCB Parameters

| Parameter | Value |
|:---:|:---:|
| **Dimensions** | 38.50 mm × 14.70 mm |
| **Board shape** | Rounded rectangle, r = 0.50 mm |
| **Finished thickness** | 1.00 mm |
| **Copper layers** | 4 |
| **Min. trace width** | 0.12 mm |
| **Min. trace spacing** | 0.12 mm |
| **Min. plated hole Ø** | 0.20 mm |
| **Min. non-plated hole Ø** | 0.65 mm |
| **Min. via outer Ø** | 0.45 mm |
| **Min. via inner Ø** | 0.20 mm |
| **Min. plated slot width** | 0.60 mm |
| **Min. non-plated slot width** | N/A |

## Project Description

This project was designed with KiCad 9.0.2.

A GitHub Actions CI/CD workflow runs DRC checks and generates manufacturing files (Gerber, etc.) automatically on every commit.

Manufacturing files are available from the [Release page](https://github.com/acha666/IP6557_Charger/releases) or the [Workflow page](https://github.com/acha666/IP6557_Charger/actions/workflows/kicad-ci.yml).

### Notes

*(This document was translated by ChatGPT.)*