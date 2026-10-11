# `iaLPSS2_I3C_MTL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_I3C_MTL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `25A22E16BFE19547CBDA604E6786582FBEDCBEBB94AAA9A5934E0F8778D28C1C` | `AB7038E5E575690BE0CAF01EC05FB72B3DA5CE97` | `A06B289C2A3A8AA9029C4FA18B714DAA` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_I3C_MTL.sys`
- **Розмір:** 156672 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO I3C Driver v2
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 70

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
