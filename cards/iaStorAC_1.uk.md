# `iaStorAC_1.sys`

[Назад до індексу](../README.uk.md) · [English version](iaStorAC_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `374565EDA562CD5B7057D5476C13E0EC7A01AF68DD83D16D05B012180811C5DE` | `8312AF32B4C10107FC70E81E2D873BBCA195D9DC` | `96FABF38ACC34E5AE48C8B3FFA422F62` |

## Метадані

- **Ім'я файлу:** `iaStorAC_1.sys`
- **Розмір:** 1034200 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Rapid Storage Technology driver 
- **Опис:** Intel(R) Rapid Storage Technology driver - x64
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
