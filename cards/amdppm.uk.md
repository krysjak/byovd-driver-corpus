# `amdppm.sys`

[Назад до індексу](../README.uk.md) · [English version](amdppm.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BF32E3E09692993E2702F4810908AAD81283411FC4222AE65FAD28CE30C04EBE` | `9F797E6A76ED5FDC25CEE3EE45CDB983F7C7969A` | `1C48AC041B65B4EB5A64C37D1EE781B3` |

## Метадані

- **Ім'я файлу:** `amdppm.sys` (Ідентичні копії: `amdppm_2.sys`)
- **Розмір:** 275944 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Processor Device Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
