# `pcmcia.sys`

[Назад до індексу](../README.uk.md) · [English version](pcmcia.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `505F1106FCB85C22FB2B68B8EBDC945A0C361EC12F8FBC4FF2C412D58BB785D9` | `B5F8CAA16B285023B3E8688CEB1E7B473D2A4DBB` | `D8A0E2B1330FFC122B9B72B0CB2A17C1` |

## Метадані

- **Ім'я файлу:** `pcmcia.sys` (Ідентичні копії: `pcmcia_1.sys`)
- **Розмір:** 156992 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** PCMCIA Bus Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
