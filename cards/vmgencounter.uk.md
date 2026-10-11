# `vmgencounter.sys`

[Назад до індексу](../README.uk.md) · [English version](vmgencounter.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BFD17E40B498AA842D59FD38E0FF128416CC6CF0AF9CB2EB7637C5E265180258` | `1586B0D36D247D38D604F377BA681F8E17B79C70` | `920813EC80D2012D5A9EF94AC35A7FEC` |

## Метадані

- **Ім'я файлу:** `vmgencounter.sys` (Ідентичні копії: `vmgencounter_1.sys`)
- **Розмір:** 58672 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Virtual Machine Generation Counter
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`, `system information set`

**Imports:** `MmMapIoSpaceEx`, `ZwSetSystemInformation`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
