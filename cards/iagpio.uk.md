# `iagpio.sys`

[Назад до індексу](../README.uk.md) · [English version](iagpio.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FAAA46F22944E043A90AE6E9F0F86AF187FC2819C563DA375B2A409347BB2C35` | `2A697703D2D8913D2874614014DAE4B0F7571601` | `9E5AECAB5F05218D9AC923E7CEA1CE15` |

## Метадані

- **Ім'я файлу:** `iagpio.sys` (Ідентичні копії: `iagpio_1.sys`)
- **Розмір:** 36352 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel(R) Corporation
- **Продукт:** Intel(R) Serial IO GPIO Controller Driver
- **Опис:** Intel(R) Serial IO GPIO Controller Driver
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
