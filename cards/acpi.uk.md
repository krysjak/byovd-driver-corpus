# `acpi.sys`

[Назад до індексу](../README.uk.md) · [English version](acpi.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7D3AA14F018867348959FB3006B7D1EE16496FDFF4DBF358CD0A0A17E61AB5DF` | `4B75CCAC8E7684FEB61262F2D24446F109ADED7D` | `2F4F3194C2A24D89FE40564488DB2AD4` |

## Метадані

- **Ім'я файлу:** `acpi.sys` (Ідентичні копії: `acpi_1.sys`)
- **Розмір:** 873984 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** ACPI Driver for NT
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `driver loading`, `physical address resolution`, `physical memory mapping`, `system information set`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `ZwLoadDriver`, `ZwSetSystemInformation`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
