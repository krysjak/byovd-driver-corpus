# `iacamera64.sys`

[Назад до індексу](../README.uk.md) · [English version](iacamera64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2262DA9DF659CB682E1F4C0FCBE9496E295858978EF4211C599A6571AEA5B3C5` | `4BA1A1159C571EA1042A654E8D4D80934DAFE271` | `131DC3C676DA77335CD98EF2579E815B` |

## Метадані

- **Ім'я файлу:** `iacamera64.sys`
- **Розмір:** 10313376 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) AVStream Camera
- **Опис:** Intel(R) AVStream Camera
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 105

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process lookup`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
