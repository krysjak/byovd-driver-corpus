# `NETwtw04_4.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw04_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7B6E3457853FE2253CB4FAB6DC9BC44684A264185169B4E295057C41ACB455C3` | `66CE7751F6146D7FFD2AD52B10843621758695BD` | `820E245D7A648B0AE32152213AFFF14C` |

## Метадані

- **Ім'я файлу:** `NETwtw04_4.sys`
- **Розмір:** 8756304 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
