# `NETwtw08_2.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw08_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4FFA7CE2AB229EBE651B4859CABE3B663FC8F2A12D63411970E6E6CADE3D9F89` | `853E7165411D249BED1BA51CF7051AFFCBBC5519` | `FFB69975E948D9752DB228E5C7826409` |

## Метадані

- **Ім'я файлу:** `NETwtw08_2.sys`
- **Розмір:** 8826216 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
