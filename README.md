<h1 align="center">
  <img src="https://raw.githubusercontent.com/Lizerium/.github/main/media/logo.png" width="32" style="vertical-align: middle;" />
  Lizerium.Game.Structs
</h1>

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
> This repository is part of the **Lizerium** ecosystem:
>
> - https://github.com/Lizerium/Lizerium.Hub

---

## What is this

`Lizerium.Game.Structs` is a map of the data layer.

There is no core logic here.  
This repository exists to:

- list game formats
- show how data is structured
- provide quick navigation to related repositories

---

## How to use it

> [!TIP]
> If you are working with Freelancer data:
>
> 1. Find the format you need
> 2. Open the corresponding repository
> 3. Work at the implementation level there

---

## Formats

### Base formats

Original and derived game formats:

- https://github.com/Lizerium/Lizerium.Game.INI
- https://github.com/Lizerium/Lizerium.Game.Dlls
- https://github.com/Lizerium/Lizerium.Game.SPH

Additional:

- CMP
- MAT
- TXM
- 3DB
- Music

---

### XML layer

Intermediate representations used for analysis and processing:

- https://github.com/Lizerium/Lizerium.Game.XML.CMP
- https://github.com/Lizerium/Lizerium.Game.XML.MAT
- https://github.com/Lizerium/Lizerium.Game.XML.TXM
- https://github.com/Lizerium/Lizerium.Game.XML.SPH
- https://github.com/Lizerium/Lizerium.Game.XML.3DB
- https://github.com/Lizerium/Lizerium.Game.XML.ALE
- https://github.com/Lizerium/Lizerium.Game.XML.ANM
- https://github.com/Lizerium/Lizerium.Game.XML.DFM
- https://github.com/Lizerium/Lizerium.Game.XML.UTF
- https://github.com/Lizerium/Lizerium.Game.XML.VMS

---

### Code Layer

- https://github.com/Lizerium/Lizerium.Game.Systems.Classes

---

### Data preparation and validation

Layer used for testing and data validation:

- prepared XML data
- configuration structures
- integration with validation systems

---

## Structure

```

Lizerium.Game.Structs
├── Base formats
└── XML layer
└── Code layer

```

---

## Important

> [!IMPORTANT]
> This is the data layer of the classic branch (Freelancer).
>
> Unity runtime, game logic, and visual systems are handled separately:
>
> - https://github.com/Lizerium/Lizerium.Unity.Structs

---

## Relations

Connected to:

- https://github.com/Lizerium/Lizerium.Frameworks.Structs — validation and testing

---

## Important

> [!TIP]
> If you need a specific format or tool — go to the corresponding repository.  
> This is only a map.
