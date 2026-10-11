# `NETwtw04_6.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw04_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0B8CD9637BE2CAA4A178E8D6E42677DE8272AC1373FF1B857AD1BDB9F0BC5E82` | `16C817866A7C9F3E236E332C2CC5253039217CC9` | `87172ED4FE0D0D1908F31C686E036F57` |

## Метадані

- **Ім'я файлу:** `NETwtw04_6.sys`
- **Розмір:** 7135504 bytes
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
