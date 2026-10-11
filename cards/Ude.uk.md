# `Ude.sys`

[Назад до індексу](../README.uk.md) · [English version](Ude.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `80009C87CB69B489F0CDB5997100DACAADF2A172907892F68067DCF0FC11F51C` | `8CCDEA39CF91CB8882EC8A565D3C63A48E212330` | `3B44A218EBADD4BD5FEE9D2529ADAF0A` |

## Метадані

- **Ім'я файлу:** `Ude.sys`
- **Розмір:** 337384 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel Telephony Stack
- **Опис:** UDE Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
