# `iaLPSS2_SPI_TGL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_SPI_TGL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D3588E5656C2CE9E51BF9EC6FE0B25807BA9762017DFE142A5FF4DC4CA85D7DB` | `E8579FA88B3B9D2BEAAEBBE1EAE86129FE959974` | `933707288E48D76229F463BEE9DAA60B` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_SPI_TGL.sys`
- **Розмір:** 155808 bytes
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
