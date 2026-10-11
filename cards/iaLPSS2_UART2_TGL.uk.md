# `iaLPSS2_UART2_TGL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_UART2_TGL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FD9E0B09E4EAA3DFBD3E1112D353D5402490C15279C51084A26FF6354C54C05F` | `646EE804040623EFCD7BA789DB8269EDC317706F` | `44097DFB2277368ACBE50A927BC234BA` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_UART2_TGL.sys`
- **Розмір:** 310432 bytes
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
