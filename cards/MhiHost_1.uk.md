# `MhiHost_1.sys`

[Назад до індексу](../README.uk.md) · [English version](MhiHost_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `37786975366D40263A730985E33D4832E87529EBD12ECD922F423EC9B3A27D45` | `9D37C09187D8A1A1C5E6E8988789DD4FD3F10D7D` | `323C6ECECFC4A583D9D2D2CC5BBE9934` |

## Метадані

- **Ім'я файлу:** `MhiHost_1.sys`
- **Розмір:** 213808 bytes
- **Архітектура:** 0x8664
- **Компанія:** Qualcomm Technologies, Inc.
- **Продукт:** Qualcomm Modem Host Interface Driver
- **Опис:** QUALCOMM Modem Host Interface Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
