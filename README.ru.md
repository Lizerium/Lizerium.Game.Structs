<h1 align="center">🎮 Lizerium.Game.Structs 🎮</h1>

<p align="center">
  Структурная карта игровых данных и форматов классической ветки Lizerium
</p>

<div align="center" style="margin: 20px 0; padding: 10px; background: #1c1917; border-radius: 10px;">
  <strong>🌐 Язык: </strong>
  
  <span style="color: #F5F752; margin: 0 10px;">
    ✅ 🇷🇺 Русский (текущий)
  </span>
  | 
  <a href="./README.md" style="color: #0891b2; margin: 0 10px;">
    🇺🇸 English
  </a>
</div>

---

> [!NOTE]
> Этот проект является частью экосистемы **Lizerium** и относится к направлению:
>
> - [`Lizerium.Hub`](https://github.com/Lizerium/Lizerium.Hub)
>
> Если вы ищете связанные инженерные и вспомогательные инструменты, начните оттуда.

## Назначение

Этот репозиторий является **структурным индексом игровых данных и форматов классической ветки** внутри экосистемы **Lizerium**.

Он не является основной реализацией, а служит как:

- карта игровых форматов и подсистем
- точка навигации по data-слою модификации
- описание ролей игровых репозиториев
- место для логической классификации игровых данных
- слой архитектурного обзора классического игрового контура

---

## Роль в экосистеме

Этот репозиторий помогает понять:

- какие проекты относятся к data-слою классической модификации
- как разделены игровые форматы, XML-представления и служебные структуры
- где находятся точки входа в обработку игровых ресурсов
- как устроена внутренняя логика data-контура
- какие слои используются для анализа, конвертации и валидации

---

## Что входит в это направление

### 1. 📦 Базовые игровые форматы

Оригинальные и производные игровые форматы, используемые в классической ветке Lizerium.

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

### 2. 🔄 XML-слой и промежуточные представления

XML-представления игровых форматов, используемые для анализа, преобразования, проверки и подготовки данных.

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

### 3. 🧪 Подготовка данных и интеграция с проверками

Слой, используемый для поддержки тестирования, обновления data-представлений и валидации игровых ресурсов.

- XML-репозитории, используемые в тестовых сценариях
- конфигурационные и вспомогательные структуры
- обновляемые data-слои, синхронизируемые с модификацией

---

## Архитектурная схема

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

## Примечание

Этот репозиторий описывает **классическую data-ветку модификации**, а не Unity-реализацию игры.

Новая игровая ветка, runtime-логика, ECS, визуальные системы и Unity-архитектура вынесены отдельно в:

- [`Lizerium.Unity.Structs`](https://github.com/Lizerium/Lizerium.Unity.Structs)

---

## Связь с другими направлениями

Данный слой связан с:

- [`Lizerium.Frameworks.Structs`](https://github.com/Lizerium/Lizerium.Frameworks.Structs) — системы тестирования и валидации
