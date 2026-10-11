# `iaLPSS2_GPIO2_MTL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_GPIO2_MTL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AA498023B592719F8E4757557012D9068CAB84941015295DC694DFA26696E76B` | `811CD89EF4D4A18D74F0C5A688180C3E056C4F88` | `8B9C2D532FF25533A67B91073BCDB908` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_GPIO2_MTL.sys`
- **Розмір:** 176128 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO GPIO Driver v2
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
