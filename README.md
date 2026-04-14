<h1 align="center">🎮 Lizerium.Game.Structs 🎮</h1>

<p align="center">
  Structural map of game data and formats for the classical Lizerium branch
</p>

<div align="center" style="margin: 20px 0; padding: 10px; background: #1c1917; border-radius: 10px;">
  <strong>🌐 Language: </strong>
  
  <a href="./README.ru.md" style="color: #F5F752; margin: 0 10px;">
    🇷🇺 Russian
  </a>
  | 
  <span style="color: #0891b2; margin: 0 10px;">
    ✅ 🇺🇸 English (current)
  </span>
</div>

---

> [!NOTE]
> This project is part of the **Lizerium** ecosystem and belongs to the following direction:
>
> - [`Lizerium.Hub`](https://github.com/Lizerium/Lizerium.Hub)
>
> If you are looking for related engineering and supporting tools, start there.

## Purpose

This repository serves as a **structural index of game data and formats for the classical branch** within the **Lizerium** ecosystem.

It is not a primary implementation, but acts as:

- a map of game formats and subsystems
- a navigation entry point for the data layer of the modification
- a description of roles for game-related repositories
- a place for logical classification of game data
- an architectural overview layer of the classical game pipeline

---

## Role in the Ecosystem

This repository helps to understand:

- which projects belong to the data layer of the classical modification
- how game formats, XML representations, and service structures are separated
- where the entry points for processing game resources are located
- how the internal logic of the data pipeline is organized
- which layers are used for analysis, conversion, and validation

---

## What’s Included in This Direction

### 1. 📦 Base Game Formats

Original and derived game formats used in the classical Lizerium branch.

- [`Lizerium.Game.INI`](https://github.com/Lizerium/Lizerium.Game.INI)
- [`Lizerium.Game.Dlls`](https://github.com/Lizerium/Lizerium.Game.Dlls)
- [`Lizerium.Game.SPH`](https://github.com/Lizerium/Lizerium.Game.SPH)

> [!TIP]
> TODO: CDN - storage.lizup.ru

- `Lizerium.Game.CMP`
- `Lizerium.Game.MAT`
- `Lizerium.Game.TXM`
- `Lizerium.Game.3DB`
- `Lizerium.Game.Music`

---

### 2. 🔄 XML Layer & Intermediate Representations

XML representations of game formats used for analysis, transformation, validation, and data preparation.

- [`Lizerium.Game.XML.CMP`](https://github.com/Lizerium/Lizerium.Game.XML.CMP)
- [`Lizerium.Game.XML.MAT`](https://github.com/Lizerium/Lizerium.Game.XML.MAT)
- [`Lizerium.Game.XML.TXM`](https://github.com/Lizerium/Lizerium.Game.XML.TXM)
- [`Lizerium.Game.XML.SPH`](https://github.com/Lizerium/Lizerium.Game.XML.SPH)
- [`Lizerium.Game.XML.3DB`](https://github.com/Lizerium/Lizerium.Game.XML.3DB)
- [`Lizerium.Game.XML.ALE`](https://github.com/Lizerium/Lizerium.Game.XML.ALE)
- [`Lizerium.Game.XML.ANM`](https://github.com/Lizerium/Lizerium.Game.XML.ANM)
- [`Lizerium.Game.XML.DFM`](https://github.com/Lizerium/Lizerium.Game.XML.DFM)
- [`Lizerium.Game.XML.UTF`](https://github.com/Lizerium/Lizerium.Game.XML.UTF)
- [`Lizerium.Game.XML.VMS`](https://github.com/Lizerium/Lizerium.Game.XML.VMS)

---

### 3. 🧪 Data Preparation & Validation Integration

A layer used to support testing, updating data representations, and validating game resources.

- XML repositories used in testing scenarios
- configuration and auxiliary structures
- updatable data layers synchronized with the modification

---

## Architecture Diagram

```text
Lizerium.Game.Structs
├── Base Formats
│   ├── LizeriumINI
│   ├── LizeriumDlls
│   ├── LizeriumCMP
│   ├── LizeriumMAT
│   ├── LizeriumTXM
│   ├── LizeriumSPH
│   └── Lizerium3DB
│
└── XML Layer
    ├── LizeriumCMPXML
    ├── LizeriumMATXML
    ├── LizeriumTXMXML
    ├── LizeriumSPHXML
    ├── Lizerium3DBXML
    ├── LizeriumALEXML
    ├── LizeriumANMXML
    ├── LizeriumDFMXML
    ├── LizeriumUTFXML
    └── LizeriumVMSXML
```

---

## Note

This repository describes the **classical data branch of the modification**, not the Unity-based implementation of the game.

The new game branch, runtime logic, ECS, visual systems, and Unity architecture are separated into:

- [`Lizerium.Unity.Structs`](https://github.com/Lizerium/Lizerium.Unity.Structs)

---

## Relation to Other Directions

This layer is connected with:

- [`Lizerium.Frameworks.Structs`](https://github.com/Lizerium/Lizerium.Frameworks.Structs) — testing and validation systems
