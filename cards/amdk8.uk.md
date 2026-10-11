# `amdk8.sys`

[Назад до індексу](../README.uk.md) · [English version](amdk8.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `42AF7DA6334F3227A48805B1C7AAA0A18E88353FB4B1BD4841EEC774ABB8E0FA` | `F441AB93C1FD9B77BF3596D72C03D03DAE81E845` | `C0C6D70C5241E48A4B285BBAF7532A24` |

## Метадані

- **Ім'я файлу:** `amdk8.sys` (Ідентичні копії: `amdk8_2.sys`)
- **Розмір:** 263680 bytes
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
