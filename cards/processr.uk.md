# `processr.sys`

[Назад до індексу](../README.uk.md) · [English version](processr.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D0B16F8BB169B8E2F2D796E7EC7AB1CADC1E9B4C61EB8B99CA719DA1A17B4441` | `80F2693197455CB80126F80FDA5A276CB6E21B33` | `766D5536999FC695B469F88BD4D2F406` |

## Метадані

- **Ім'я файлу:** `processr.sys` (Ідентичні копії: `processr_2.sys`)
- **Розмір:** 275928 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Processor Device Driver
- **Підпис:** signed
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
