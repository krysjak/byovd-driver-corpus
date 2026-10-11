# `amdppm_1.sys`

[Назад до індексу](../README.uk.md) · [English version](amdppm_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8ED7A1C9E16691D3439208895CEFAE9B590B3FD8DC2C44AEF29DA358A8FBC55D` | `A22820E598D2DC10335276A58E2BA7B32DB9B5DD` | `1A13962D37AEA3A0C505E7E1D109274D` |

## Метадані

- **Ім'я файлу:** `amdppm_1.sys` (Ідентичні копії: `amdppm_3.sys`)
- **Розмір:** 271776 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Processor Device Driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
