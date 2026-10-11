# `NETwew01_1.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwew01_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `CF30F6D08AA7FC9EAA453B6273ABB92541C1C317C842F0EA690355734A68E2A6` | `48FA8E24C44301DDBFC0E5553BD4E8733B390149` | `8259EF516F176EA37BD074F42DE78C78` |

## Метадані

- **Ім'я файлу:** `NETwew01_1.sys`
- **Розмір:** 3354384 bytes
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
