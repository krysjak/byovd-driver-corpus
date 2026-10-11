# `NETwtw04_3.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw04_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9061F3EED629715595DEEE4486AA579423773794FF858DBC2C17F9B1412B2FD7` | `7201EF7CF6AC93D88D5041BD64531B64CA177315` | `2F64555DF33E8A547145FE6CF5A4D485` |

## Метадані

- **Ім'я файлу:** `NETwtw04_3.sys`
- **Розмір:** 8776360 bytes
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
