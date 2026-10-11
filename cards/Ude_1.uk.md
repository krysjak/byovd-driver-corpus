# `Ude_1.sys`

[Назад до індексу](../README.uk.md) · [English version](Ude_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `45A5B65F5605F9B264504AE958897AB9C47F88D4A7CAF392A031FDA141470D04` | `E0D137893284814DDEB418AD3F304469AB2F59C6` | `1047DDE8EFDC2D1C77AD55A0C11F4EEE` |

## Метадані

- **Ім'я файлу:** `Ude_1.sys`
- **Розмір:** 351672 bytes
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
