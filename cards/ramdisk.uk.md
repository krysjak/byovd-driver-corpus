# `ramdisk.sys`

[Назад до індексу](../README.uk.md) · [English version](ramdisk.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E706C3C549860D3EB848D30FBD2EA9DBF5E2A96A11F050FD93F73FCA53EECFB3` | `426FA2A51C02A592E31145684D3F4BAD619F6A25` | `3EEC837D3CEBC183CF2AB5272D065B99` |

## Метадані

- **Ім'я файлу:** `ramdisk.sys` (Ідентичні копії: `ramdisk_1.sys`)
- **Розмір:** 75232 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** RAM Disk Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
