# `ISH_1.sys`

[Назад до індексу](../README.uk.md) · [English version](ISH_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B9D675E8D0E47D3714B6A2FD8CE0D0470EE69F4A25B35607FE5E88FFBC2D66A2` | `2C25B83650146F2AF012F1B1E8088D10D1601610` | `EF49FFC12A54AB06AFACF3192412EA53` |

## Метадані

- **Ім'я файлу:** `ISH_1.sys`
- **Розмір:** 161680 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel
- **Продукт:** ISS
- **Опис:** Intel(R) Integrated Sensor Solution
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
