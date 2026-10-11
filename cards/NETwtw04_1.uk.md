# `NETwtw04_1.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw04_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B91A1F2786065CF788A6C2C016A09A89B3117F4E6BC93A3E3C71868640125D50` | `186F56014EE0B9A7D0CA409213D526641A60DC0C` | `C4CAAFE8C6A996D1A5AF306AAB021F12` |

## Метадані

- **Ім'я файлу:** `NETwtw04_1.sys`
- **Розмір:** 8654184 bytes
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
