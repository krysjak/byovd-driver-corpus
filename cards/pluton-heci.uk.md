# `pluton-heci.sys`

[Назад до індексу](../README.uk.md) · [English version](pluton-heci.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `534A771165BDA8CB30BC856F69ACF624B98B810196873AE3306FCB6703A3CA09` | `9B0F6FC1C2BBB5BEA2FBAD2505A811C259060F29` | `8D3AAA6796553ED6952BCF079E5ADCE9` |

## Метадані

- **Ім'я файлу:** `pluton-heci.sys`
- **Розмір:** 95704 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Pluton HECI Device Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
