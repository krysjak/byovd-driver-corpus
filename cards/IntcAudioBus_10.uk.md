# `IntcAudioBus_10.sys`

[Назад до індексу](../README.uk.md) · [English version](IntcAudioBus_10.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `189A880190319C5CC078AB1511256690D1E5B6C1032C29FC6739017A5EF9BCD4` | `80E0090D3488F64D0D8C4EB22D68E3FFEA41A952` | `1B83A5686B7682AA7515E038AEBA98FE` |

## Метадані

- **Ім'я файлу:** `IntcAudioBus_10.sys`
- **Розмір:** 292936 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel(R) Corporation
- **Продукт:** Intel® Smart Sound Technology (Intel® SST) Bus
- **Опис:** Intel® Smart Sound Technology (Intel® SST) Bus
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
