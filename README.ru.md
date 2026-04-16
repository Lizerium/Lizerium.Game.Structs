<h1 align="center">
  <img src="https://raw.githubusercontent.com/Lizerium/.github/main/media/logo.png" width="32" style="vertical-align: middle;" />
  Lizerium.Game.Structs
</h1>

<p align="center">
  Карта игровых форматов и data-слоя Lizerium (Freelancer)
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
> Этот репозиторий — часть экосистемы **Lizerium**:
>
> - https://github.com/Lizerium/Lizerium.Hub

---

## Что это

`Lizerium.Game.Structs` — это карта data-слоя.

Здесь нет основной логики.  
Репозиторий нужен, чтобы:

- видеть игровые форматы
- понимать, как устроены данные
- быстро переходить к нужным репозиториям

---

## Как этим пользоваться

> [!TIP]
> Если ты работаешь с данными Freelancer:
>
> 1. Найди нужный формат
> 2. Перейди в соответствующий репозиторий
> 3. Работай уже на уровне конкретной реализации

---

## Форматы

### Базовые форматы

Оригинальные и производные форматы игры:

- https://github.com/Lizerium/Lizerium.Game.INI
- https://github.com/Lizerium/Lizerium.Game.Dlls
- https://github.com/Lizerium/Lizerium.Game.SPH

Дополнительно:

- CMP
- MAT
- TXM
- 3DB
- Music

---

### XML слой

Промежуточные представления для анализа и обработки:

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

### Подготовка и проверка данных

Слой, связанный с тестированием и валидацией:

- подготовленные XML-данные
- конфигурационные структуры
- интеграция с проверками

---

## Структура

```

Lizerium.Game.Structs
├── Base formats
└── XML layer

```

---

## Важно

> [!IMPORTANT]
> Это слой данных классической ветки (Freelancer).
>
> Unity-логика, runtime и визуальные системы находятся отдельно:
>
> - https://github.com/Lizerium/Lizerium.Unity.Structs

---

## Связи

Связан с:

- https://github.com/Lizerium/Lizerium.Frameworks.Structs — валидация и тестирование

---

## Важно

> [!TIP]
> Если тебе нужен конкретный формат или инструмент — переходи в соответствующий репозиторий.  
> Здесь только карта.
