# `fdc.sys`

[Назад до індексу](../README.uk.md) · [English version](fdc.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `ACE9195D382EED208D1C64AE2452B8FA4D55329C5E23086D7A341C0ED19B8803` | `85D67588BB26C6E36D4958D646968D4E31A743DA` | `FF4D08D19AA23EAFFE1D594C382E5F2D` |

## Метадані

- **Ім'я файлу:** `fdc.sys` (Ідентичні копії: `fdc_1.sys`)
- **Розмір:** 69632 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Floppy Disk Controller Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
