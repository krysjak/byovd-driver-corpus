# `NETwbn02.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwbn02.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `263F75E89766607C459BCF06C9CBBF340F8A5897FA7410D3006A86F26096AD51` | `77F38889EDE408144963A212C089911197BA6CE1` | `0FB8D7434499380EC5DB138B507645B6` |

## Метадані

- **Ім'я файлу:** `NETwbn02.sys`
- **Розмір:** 2859288 bytes
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
