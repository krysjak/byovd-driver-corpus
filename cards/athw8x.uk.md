# `athw8x.sys`

[Назад до індексу](../README.uk.md) · [English version](athw8x.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DE129E570C85EE8AAE8084B40F4E32766B4B789A2EED81E46311712B0826053D` | `E649EAC3D9680CD11D26C2F4C8EAC60040889BC6` | `835E2C1A3D32492E2B90BD4FE5527CB6` |

## Метадані

- **Ім'я файлу:** `athw8x.sys`
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
