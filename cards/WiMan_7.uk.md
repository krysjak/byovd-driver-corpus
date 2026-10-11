# `WiMan_7.sys`

[Назад до індексу](../README.uk.md) · [English version](WiMan_7.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9282E6072EE1CA053D78FDC3639A7D2D8BADC60BB2426539CAC091680B89A1EB` | `33EB57DFA68FAA49F3E0C2B80ACD445E02973334` | `E3D6C44B498B9F74A799091360AB5148` |

## Метадані

- **Ім'я файлу:** `WiMan_7.sys`
- **Розмір:** 166480 bytes
- **Архітектура:** 0x8664
- **Компанія:** —
- **Продукт:** —
- **Опис:** —
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
