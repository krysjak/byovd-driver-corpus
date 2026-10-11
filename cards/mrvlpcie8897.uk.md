# `mrvlpcie8897.sys`

[Назад до індексу](../README.uk.md) · [English version](mrvlpcie8897.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `72EE4E962868C1C345A8D4E93ADE0CCD919C369471DE4D049BEF59BD3642407B` | `CF9842B5EA9951FA08438D6764A4873B3554424A` | `5ADE5BC51D4330F39C1AB27C5D17A46C` |

## Метадані

- **Ім'я файлу:** `mrvlpcie8897.sys`
- **Розмір:** 1036288 bytes
- **Архітектура:** 0x8664
- **Компанія:** Marvell Semiconductors Inc.
- **Продукт:** Marvell LE Driver
- **Опис:** Marvell LE Driver for the WiFiCLass Stack
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
