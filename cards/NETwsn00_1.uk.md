# `NETwsn00_1.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwsn00_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8B26380D3FDE8D6BD6124EBC973D378D51FD0BC5801A8BA15EB4ADDD6A6BBFED` | `04810EE59A9EC0CF67CB8B695A94F934807176FD` | `2E6EE6C80A69313F7B7100AB573A5D0C` |

## Метадані

- **Ім'я файлу:** `NETwsn00_1.sys`
- **Розмір:** 10383264 bytes
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
