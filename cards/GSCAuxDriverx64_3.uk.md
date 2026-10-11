# `GSCAuxDriverx64_3.sys`

[Назад до індексу](../README.uk.md) · [English version](GSCAuxDriverx64_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7FC9DD9EE124F72ACFCD299AC40A3D92B239E6C35ABDAF0F3A4D5CB78F6A71BA` | `1729C80A238E38202630DC40C35923A09DE05143` | `EA9B0CD2E96D920B38D530189ACD05F2` |

## Метадані

- **Ім'я файлу:** `GSCAuxDriverx64_3.sys`
- **Розмір:** 102344 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
- **Опис:** Intel(R) Graphics System Controller Auxiliary Firmware Interface
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
