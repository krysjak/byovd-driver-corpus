# `PRI-Driver_1.sys`

[Назад до індексу](../README.uk.md) · [English version](PRI-Driver_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `36F85A96E6595F547D3C5E6E13C901BAD6E8CF559FCC63E8494CA491B2094BA2` | `AB1F6ED7D9988CAA44C6D8CB6365346C7776885F` | `FF79EEC09B74DDD8FEC59C37D8535F88` |

## Метадані

- **Ім'я файлу:** `PRI-Driver_1.sys`
- **Розмір:** 378008 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Platform Register Interface Driver
- **Опис:** Intel(R) Platform Register Interface Driver 
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
