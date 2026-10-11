# `NETwtw08_12.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw08_12.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6CB9A2EBB003CDDBFE5C3AB5D5FAEA4ED14E146440ED95CB7CFF1623B0084E74` | `4F7E9E52A0DA364AA4EFCFF2DAEB2297288EEA7A` | `0D4DB9659B93FFCDC0C6A1AC7BB256D1` |

## Метадані

- **Ім'я файлу:** `NETwtw08_12.sys`
- **Розмір:** 8833808 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
