# `vhdmp.sys`

[Назад до індексу](../README.uk.md) · [English version](vhdmp.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `690C256F6C5045ADBEB68452A0147F802A89B3BCD49532CAA26C89654113C739` | `BC44D9A418417D89469C9E7CA92494D387253A75` | `150CA9EDAC79C3EA1D3333FE35624763` |

## Метадані

- **Ім'я файлу:** `vhdmp.sys` (Ідентичні копії: `vhdmp_1.sys`)
- **Розмір:** 1058288 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** VHD Miniport Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `section mapping (kernel R/W surface)`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`, `ZwMapViewOfSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
