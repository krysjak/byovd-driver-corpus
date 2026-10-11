# `iaLPSS2_SPI_MTL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_SPI_MTL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7BAD7E42C8D94B7AE680DA5161EF8454E77F526635763D04E6B3978152DAE637` | `A3611BFDEBE9F9B344E9025508D7B3603D46C467` | `B3A733E3A69FDDCBB5B074CD8C7F6AC8` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_SPI_MTL.sys`
- **Розмір:** 163328 bytes
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
