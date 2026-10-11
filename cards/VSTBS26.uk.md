# `VSTBS26.SYS`

[Назад до індексу](../README.uk.md) · [English version](VSTBS26.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A76C0371E9E18B038B0745C3F38AC4E958D43CB87EAB358EB88F431A33EE1F6E` | `170AC0369FE03CDD15D08AB782485180CB1005DA` | `93132C69394A99D992095D8CFE464801` |

## Метадані

- **Ім'я файлу:** `VSTBS26.SYS` (Ідентичні копії: `VSTBS26_1.SYS`)
- **Розмір:** 411136 bytes
- **Архітектура:** 0x8664
- **Компанія:** Conexant Systems, Inc.
- **Продукт:** SoftK56 Modem Driver
- **Опис:** HSF_HWB2 WDM driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
