# `GSCAuxDriverx64_7.sys`

[Назад до індексу](../README.uk.md) · [English version](GSCAuxDriverx64_7.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1A7FD4FEF369E14528AA6E8012E0268BB6F3E4582BFCAC9096A88812E879CA24` | `B4966501901A1A0A93D79AC92D4D40C29701A50B` | `6222F1237337D6930E897E2FB12B6E79` |

## Метадані

- **Ім'я файлу:** `GSCAuxDriverx64_7.sys`
- **Розмір:** 109248 bytes
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
