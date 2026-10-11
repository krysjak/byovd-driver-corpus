# `WiMan_4.sys`

[Назад до індексу](../README.uk.md) · [English version](WiMan_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A6FDDFC294036629748A17A60063554323D1F22E8685132EC4DB6720493E5632` | `B56F0A4E350FF3304ABC85777AB4D03B30396ACF` | `8125694C73B64920259FFFD421AFCA8D` |

## Метадані

- **Ім'я файлу:** `WiMan_4.sys`
- **Розмір:** 170576 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless Manageability
- **Опис:** Intel® Wireless Manageability
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
