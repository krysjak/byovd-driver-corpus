# `iaLPSS2_SPI_TGL_1.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_SPI_TGL_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F8586E68B8555753E16CBECE50345716197C81535A69F02C486653CB3CCAC2AD` | `D590007405714DDC9075E00D9A89968B9E8A9C04` | `AAB13970FA31A7B83B6AAED663DC7235` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_SPI_TGL_1.sys`
- **Розмір:** 158352 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO SPI Driver v2
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
