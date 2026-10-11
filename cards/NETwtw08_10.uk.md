# `NETwtw08_10.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw08_10.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D1DBA7B9EF22530605320E1C97CCBAAEC26D77F8E9025A938B6C106BA4A412D3` | `B52B28321D2D0DFF16628408727ADCEF4843F065` | `BF235B41CAB8C7F3215DF9360B9A6013` |

## Метадані

- **Ім'я файлу:** `NETwtw08_10.sys`
- **Розмір:** 8814160 bytes
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
