# `NETwtw06_5.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw06_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8FD8276CB417D8116C21E2F5D88B7351C4BA5C433F42E31F542FA6FEDC80D594` | `D896E717AAB750AAC5DA155BAAB68BCF50ABECFF` | `8E734C73488DEB8A73FDEE1388586E62` |

## Метадані

- **Ім'я файлу:** `NETwtw06_5.sys`
- **Розмір:** 8827168 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
