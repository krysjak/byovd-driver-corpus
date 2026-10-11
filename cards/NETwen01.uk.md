# `NETwen01.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwen01.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6BCD7E2F9AE09C75D06FF4A726C14295FB51316D921E82A08039D21406217E14` | `606AA25B7676B1B543BBEC462EB55242F1AEDAFE` | `C6A47B304C01A3B7DBD281EDF2369C5E` |

## Метадані

- **Ім'я файлу:** `NETwen01.sys`
- **Розмір:** 2681104 bytes
- **Архітектура:** 0x14c
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
