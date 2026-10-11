# `AtihdWT6.sys`

[Назад до індексу](../README.uk.md) · [English version](AtihdWT6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BA04C1DEDDC62380548A34681A320DF644EBA0C387576953B50C7A05CD8CA012` | `3F2FC6CDCF9AFE7B4329354259C4F891A6D08910` | `50DC0AA74FBA44D93F8B5B7C96E90FCA` |

## Метадані

- **Ім'я файлу:** `AtihdWT6.sys`
- **Розмір:** 255304 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices
- **Продукт:** AMD HD Audio Driver
- **Опис:** AMD High Definition Audio Function Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
