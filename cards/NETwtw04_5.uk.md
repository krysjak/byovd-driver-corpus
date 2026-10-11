# `NETwtw04_5.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw04_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5C4022C6F3035BFF1E789D6AB8BC2D3A5878169D66BECD19091A1CF83BD57BD2` | `172D239C1654A0279800AA96FE3875AEE3605B2D` | `677C20DC57EA8232313BDDEBE109FAD8` |

## Метадані

- **Ім'я файлу:** `NETwtw04_5.sys`
- **Розмір:** 8720384 bytes
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
