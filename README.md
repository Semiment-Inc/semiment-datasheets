# Semiment Datasheet Repository

E*nglish datasheets (specification sheets) for Semiment (赛卓电子) IC products, organized by product family.*

*This repository* collects the **English (EN)** versions of Semiment datasheets only. Files are grouped into eight top-level categories that mirror the company's product portfolio.

## Repository Structure

```
.
├── 1.SpeedSensor/              # Speed & position sensors for powertrain (22 files)
│   ├── CamshaftSensor/
│   ├── CrankSensor/
│   ├── GeartoothEncoder/
│   ├── TransmissionSensor/
│   └── WheelSpeedSensor/
├── 2.MagneticPositionSensor/   # Magnetic position sensing (51 files)
│   ├── LinearHall/
│   └── SwitchHall/
│       ├── Dual Channel Switch Hall/
│       ├── Latch Switch Hall/
│       ├── Ominipolar Switch Hall/
│       └── Unipolar Switch Hall/
├── 3.CurrentSensor/            # Current sensors (6 files)
│   ├── Coreless/
│   └── ProgrammableLinearHall/
├── 4.AngleSensor/              # Angle / 3D Hall angle sensors (7 files)
├── 5.HighSpeedEncoder/         # High-speed encoders (18 files)
│   ├── Inductive/
│   └── Magnetic/
├── 6.MotorDrivers/             # Motor driver ICs (4 files)
│   ├── DirectBrushlessMotorDriver/
│   └── FanDriver/
├── 7.PowerManagement/          # Power management ICs (11 files)
│   ├── BuckBoost Controller/
│   ├── LDO/
│   ├── PMIC/
│   └── Switch Regulator/
└── 8.Others/                   # Other devices (2 files)
    └── OP/                     # Operational amplifiers
```

| # | Category               | Description                                                       | EN files |
| - | ---------------------- | ----------------------------------------------------------------- | -------: |
| 1 | SpeedSensor            | Camshaft / crank / geartooth / transmission / wheel-speed sensors |       22 |
| 2 | MagneticPositionSensor | Linear Hall & switch Hall sensors                                 |       51 |
| 3 | CurrentSensor          | Coreless & programmable linear-Hall current sensors               |        6 |
| 4 | AngleSensor            | Single & 3D Hall angle sensors                                    |        7 |
| 5 | HighSpeedEncoder       | Inductive & magnetic high-speed encoders                          |       18 |
| 6 | MotorDrivers           | BLDC / fan motor driver ICs                                       |        4 |
| 7 | PowerManagement        | Buck-boost, LDO, PMIC, switch regulators                          |       11 |
| 8 | Others                 | Operational amplifiers and misc. devices                          |        2 |
|   | **Total**              |                                                                   |  **121** |

## File Naming Convention

```
<PartNumber>_<Language>_V<Major>.<Minor>.pdf
```

- **Language**: `EN` for English. (Chinese versions are not included in this repository.)
- **Version**: `Vx.y` indicates the datasheet revision, e.g. `V1.2`.

Examples:

- `SC4671_EN_V1.2.pdf` — Semiment SC4671, English, revision 1.2
- `SC69431Q_EN_V1.0.pdf` — Semiment SC69431Q, English, revision 1.0

## How to Locate a Datasheet

1. Identify the product family from the part number prefix or the application, then open the matching top-level folder (1–8).
2. Drill into the sub-folder if the category is split (e.g. `2.MagneticPositionSensor/LinearHall`).
3. Search the folder for the exact part number, or filter by the `_EN_` token to list all English datasheets.

## Notes

- This repository contains **English datasheets only**. Chinese (`_CN_`) versions are maintained separately and are not part of this tree.
- Datasheet content and revision numbers are authoritative as published; always confirm the latest revision against the official Semiment documentation before design-in.
- Product naming follows Semiment's internal convention; cross-reference the part number rather than the file path when in doubt.
