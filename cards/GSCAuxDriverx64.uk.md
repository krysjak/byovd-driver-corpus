# `GSCAuxDriverx64.sys`

[Назад до індексу](../README.uk.md) · [English version](GSCAuxDriverx64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C215CEFF62CA811CA55986E6646E9CCF6C8891CCFE6519862039CD7B7886D606` | `966F09BD5A48FBEC99F7D9F4762B025EF6E9F4CF` | `8D76875C9E13C70D167ACA9F5F435402` |

## Метадані

- **Ім'я файлу:** `GSCAuxDriverx64.sys`
- **Розмір:** 85728 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
- **Опис:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
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
