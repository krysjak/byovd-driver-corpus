# `sdbus.sys`

[Назад до індексу](../README.uk.md) · [English version](sdbus.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C1E9481B69992105ADDA6D0E0AE577452F3CE8714CA3F5C7ECB55DF2D0897479` | `67FFA0AED6D88DA4B77C7F4CF7BEDADBA81F54F1` | `0BAA91899707D0A70A842D5C126FA698` |

## Метадані

- **Ім'я файлу:** `sdbus.sys` (Ідентичні копії: `sdbus_1.sys`)
- **Розмір:** 345560 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** SecureDigital Bus Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
