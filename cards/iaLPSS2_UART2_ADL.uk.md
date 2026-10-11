# `iaLPSS2_UART2_ADL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_UART2_ADL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `A7AE12D6AFE9CFEA7EFC636B37A1FF7B0E3190DF64DA9C5BBD66272E461C0E0E` | `31EEDE1E78C53ACD645B0775F84867E70153915D` | `8FC8158496B4C3BA378BA7A1F96DC6E1` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_UART2_ADL.sys`
- **Розмір:** 329320 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO UART Driver
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
