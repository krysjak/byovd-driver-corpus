# `Netwen02.sys`

[Назад до індексу](../README.uk.md) · [English version](Netwen02.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0FA9A79E129EF6F1AABA736A171E2C48CEBA07447206110A3096DE59474C3779` | `68CFA7B76AFA7528549502DA9FBEBB8D27486E78` | `6D4D255973E2B002160E62986E7369DF` |

## Метадані

- **Ім'я файлу:** `Netwen02.sys`
- **Розмір:** 2964448 bytes
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
