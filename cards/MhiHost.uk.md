# `MhiHost.sys`

[Назад до індексу](../README.uk.md) · [English version](MhiHost.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5054E023AD7C3013CA80DCD0A469183825B2E6951AB81BEF5A3B5232DB2F0055` | `4F284F7C9A637CAF5A8E50DC8596239C375CE3C6` | `56643D8DAE3E981A4A49173816837090` |

## Метадані

- **Ім'я файлу:** `MhiHost.sys`
- **Розмір:** 175952 bytes
- **Архітектура:** 0x8664
- **Компанія:** Qualcomm Technologies, Inc.
- **Продукт:** Qualcomm Modem Host Interface Driver
- **Опис:** QUALCOMM Modem Host Interface Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
