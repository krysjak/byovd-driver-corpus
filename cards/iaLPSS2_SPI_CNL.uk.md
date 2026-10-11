# `iaLPSS2_SPI_CNL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_SPI_CNL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `503BBB5153F588A919F17E991D67D1988445724B28F0154072FF63E96AEAE1E6` | `22DBBCBB9272ED835B3EC91DD1FA263F951E344B` | `2D1BB7A9DB8993A1441043A79D15EBA5` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_SPI_CNL.sys`
- **Розмір:** 156936 bytes
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
