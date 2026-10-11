# `athw10x.sys`

[Назад до індексу](../README.uk.md) · [English version](athw10x.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7C65FE533B4A93CA3621032A49260320E190684EE797A69B90B5C4C457CA457E` | `F51F884301F263B60350C98F9D71BB4F8EA323EA` | `2557EF2B68CB9AC8E06D9EE54450DE1A` |

## Метадані

- **Ім'я файлу:** `athw10x.sys`
- **Розмір:** 4317112 bytes
- **Архітектура:** 0x8664
- **Компанія:** Qualcomm Atheros Communications, Inc.
- **Продукт:** Driver for Qualcomm Atheros CB42/CB43/MB42/MB43 Network Adapter
- **Опис:** Qualcomm Atheros Extensible Wireless LAN device driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 105

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
