# `rteth.sys`

[Назад до індексу](../README.uk.md) · [English version](rteth.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AD633FAB8A7B61337B9EF6AD7651F213BFEADC2CAA741AF95DBF20E5C3EC8BCE` | `E810F67F541FC664B3991F8A2D0E0B8DB25515B4` | `30993B838ACFB0F1D6F2B416A40BBA76` |

## Метадані

- **Ім'я файлу:** `rteth.sys`
- **Розмір:** 86016 bytes
- **Архітектура:** 0x8664
- **Компанія:** Realtek
- **Продукт:** Realtek PCIe GBE Family Adapters
- **Опис:** Realtek PCIe GBE Family Controller Flight
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
