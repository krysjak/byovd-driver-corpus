# `NETwbw02_1.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwbw02_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BD748008FF334BB40502937F20F0B30A7096361BB56DBE4A8C4DD67066D5B660` | `80EA17FBFB0FFF7C28466D02BBA625C2CB589A8E` | `57B8053A3C2A01A2C2A2DB2577D653DB` |

## Метадані

- **Ім'я файлу:** `NETwbw02_1.sys`
- **Розмір:** 3515664 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
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
