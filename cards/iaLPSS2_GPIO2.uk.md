# `iaLPSS2_GPIO2.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_GPIO2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1D6361B5FF49DC4490895698AC715A0FBF8DF304464E3FFF56DE210DC63B30A9` | `3D4B54F9C40EF0A970F0B55B182948DCF6FF82D4` | `9FE4CB3929DFC9571756B45A9988FF71` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_GPIO2.sys`
- **Розмір:** 113272 bytes
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
