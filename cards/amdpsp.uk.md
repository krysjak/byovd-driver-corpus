# `amdpsp.sys`

[Назад до індексу](../README.uk.md) · [English version](amdpsp.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3A93FDD9EB697AD67C765CACC307857B431032A7147DA47C1D7698D124C70615` | `094843FB26C506E5050AF4593B67579605B6146C` | `95402B931830D9BAC56AFE837D732A1A` |

## Метадані

- **Ім'я файлу:** `amdpsp.sys` (Ідентичні копії: `amdpsp_2.sys`)
- **Розмір:** 70144 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc. 
- **Продукт:** Advanced Micro Devices, Inc. amdpsp sys
- **Опис:** amdpsp sys
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
