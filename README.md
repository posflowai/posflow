# PosFlow — Cloud-Native GNSS Data Processing Platform

**[PosFlow](https://posflow.ai)** is a browser-based geodetic and GNSS data processing platform built for surveyors, UAV photogrammetry teams, CORS operators, and geodesy researchers.

## Core Modules

- **Flux (Format Conversion)** — Convert raw receiver logs (u-blox `.ubx`, Septentrio `.sbf`, Trimble `.t00/.t01/.t02/.t04/.dat`, Leica `.mdb/.m00`, Topcon `.tps`, Javad `.jps`, NovAtel OEM, BINEX, RTCM3, Hatanaka `.crx`) to standard RINEX 2/3/4 (2.00–4.02) in the cloud.
- **Crux (Quality Control)** — Score RINEX observation files (0–100) across GPS, GLONASS, Galileo, BeiDou, and QZSS with completeness, multipath, cycle-slip, and SNR diagnostics (Fast, Flash, Full, and TEQC-compatible modes). Includes a free anonymous Quick Check (up to 100 MB / 20 MB gzipped, 2 checks/day).
- **Apex (Precise Positioning)** — Cloud Static/Kinematic PPP, rover-base PPK, GNSS network adjustment, and **Apex Duo** independent dual-engine cross-verification (Pro plan or pay-per-use credit packs).
- **Axis (Coordinate Transformation)** — Single-point and batch transformations across WGS84, CGCS2000, ITRF2008/2014/2020, ETRS89, NAD83, UTM, Gauss-Krüger, geoid models, and EPSG codes.

## Developer Ecosystem

- TypeScript / JavaScript SDK: `@posflow/sdk`
- Python SDK: `posflow`
- Model Context Protocol Server: `@posflow/mcp-server`

Website: [https://posflow.ai](https://posflow.ai) · Docs: [https://posflow.ai/docs](https://posflow.ai/docs) · Pricing: [https://posflow.ai/pricing](https://posflow.ai/pricing)
