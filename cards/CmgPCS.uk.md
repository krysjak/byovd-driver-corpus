# `CmgPCS.sys`

[Назад до індексу](../README.uk.md) · [English version](CmgPCS.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DA0F3F70DC51D0EAC03B4D279D95687D7E4C546C9820B146292E3E1BFFDE605E` | `EA0630194FFD036672C7BB86731AA92B305AC6B0` | `6D2DD3B75C463F3E6495E3D5206089E8` |

## Метадані

- **Ім'я файлу:** `CmgPCS.sys`
- **Розмір:** 143968 bytes
- **Архітектура:** 0x14c
- **Компанія:** Dell Inc.
- **Продукт:** CmgPCS.sys (32b,rls)
- **Опис:** Port Controls Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 110

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
