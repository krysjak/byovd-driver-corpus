# `dlusbaudio_1.sys`

[Назад до індексу](../README.uk.md) · [English version](dlusbaudio_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B144E08634AC0805CCC03C449AC21CFA3A3D69862F0065DA6421E8A0F534D0B6` | `BA7B67C2E79CABB3152288054B992953E70DFFC8` | `F21FFDD07864F70179A0DB1F1DC17D47` |

## Метадані

- **Ім'я файлу:** `dlusbaudio_1.sys`
- **Розмір:** 177424 bytes
- **Архітектура:** 0x14c
- **Компанія:** DisplayLink Corp.
- **Продукт:** DisplayLink USB Audio 2.0 Class Driver
- **Опис:** DisplayLink USB Audio Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
