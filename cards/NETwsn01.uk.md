# `NETwsn01.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwsn01.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6051BB3DBE2B9CC4B7B38018A400FFB91ABB23C3712B0B184103A5BE4BD25772` | `0957F40D17415DCBFF6994D0EB568E1659CCE7F4` | `D98FD0EF9CF9BBD03FFBA1140E9C8E65` |

## Метадані

- **Ім'я файлу:** `NETwsn01.sys`
- **Розмір:** 10385824 bytes
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
