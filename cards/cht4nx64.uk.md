# `cht4nx64.sys`

[Назад до індексу](../README.uk.md) · [English version](cht4nx64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0F03752E6E8D4E9E2B648BEA26AD2D577A13454D929AAC57F0B0E1835CD15B19` | `7DA07E996E705F3EAB5454E1F9B8D9E91D5B2EE4` | `26FA1F3228DD627CC772D7F98A066D4D` |

## Метадані

- **Ім'я файлу:** `cht4nx64.sys`
- **Розмір:** 537904 bytes
- **Архітектура:** 0x8664
- **Компанія:** Chelsio Communications
- **Продукт:** Chelsio Communications Unified Network I/O Controller
- **Опис:** Chelsio Communications Unified Network I/O Controller Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
