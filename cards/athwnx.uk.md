# `athwnx.sys`

[Назад до індексу](../README.uk.md) · [English version](athwnx.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8047E2D20724B464B481F06C3AC1FA5734E97F7EC0D86EFEECD76480C84B3959` | `5812318223F19FA476039EC97E00EA6D46E367F0` | `D03E551165C72F2A4BBDDC566EAA819E` |

## Метадані

- **Ім'я файлу:** `athwnx.sys`
- **Розмір:** 4233728 bytes
- **Архітектура:** 0x8664
- **Компанія:** Qualcomm Atheros Communications, Inc.
- **Продукт:** Driver for Qualcomm Atheros CB42/CB43/MB42/MB43 Network Adapter
- **Опис:** Qualcomm Atheros Extensible Wireless LAN device driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
