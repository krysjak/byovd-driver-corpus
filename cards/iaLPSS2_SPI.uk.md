# `iaLPSS2_SPI.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_SPI.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9E6873BFFFA91D33FC59C481068AE9E8EDCE108F0FADD82E46375CF7DF765AD3` | `883F7D5D46E0D74FFA2DADC6687EFF6DA7D09094` | `291F56FDA7E4A53E3F14D9C3BEB8996B` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_SPI.sys`
- **Розмір:** 159352 bytes
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
