# `NETwaw10_1.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwaw10_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `331439D432E7D53B9BD0929E50D11AFDC762CA7383BC6A571349197F9E7BC2CC` | `97F6DB3950BDC592A8180A7E93A68430FB7FDA39` | `BF878FC86FEB2379C60AD6A26902E009` |

## Метадані

- **Ім'я файлу:** `NETwaw10_1.sys`
- **Розмір:** 5040728 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** R Intel Wireless WiFi Link Driver
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
