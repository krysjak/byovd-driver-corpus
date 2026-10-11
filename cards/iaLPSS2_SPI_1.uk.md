# `iaLPSS2_SPI_1.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_SPI_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4D3FB8CEBF0D5F1A4A24EC80126BC4E68EDF289C3683FD6C93E8B3048EC69015` | `B1D5DB71CFCE1E68421B034184F453142FBF633A` | `0872F31ACD7B6EF9FFD48F2CBCF67FDD` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_SPI_1.sys`
- **Розмір:** 156768 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO SPI Driver v2
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
