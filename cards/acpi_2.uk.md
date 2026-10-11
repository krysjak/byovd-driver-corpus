# `acpi_2.sys`

[Назад до індексу](../README.uk.md) · [English version](acpi_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D69D673224EB9F899180E2D3CC32DA12AE8299437D51EBC2D8E96266B4C33DA0` | `9EC1E7F82EF2D3CF4004743DFB4A72D88B1F8DBC` | `8905324CCD30FBE5AF95C0B652ED71DE` |

## Метадані

- **Ім'я файлу:** `acpi_2.sys` (Ідентичні копії: `acpi_3.sys`)
- **Розмір:** 873856 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** ACPI Driver for NT
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 140

## Профіль можливостей

**Primitives:** `driver loading`, `physical address resolution`, `physical memory mapping`, `system information set`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `ZwLoadDriver`, `ZwSetSystemInformation`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
