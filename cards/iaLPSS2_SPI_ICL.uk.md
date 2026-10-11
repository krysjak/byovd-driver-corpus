# `iaLPSS2_SPI_ICL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_SPI_ICL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7B66688534832295A9A7A5AE582DB9F0B1B7FADCD37022BBB682670F3633242D` | `C3A821A6F587A2123E76A5E273A2C65172977DD3` | `D709D4B211A65B870709BDA81FA7E10B` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_SPI_ICL.sys`
- **Розмір:** 160024 bytes
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
