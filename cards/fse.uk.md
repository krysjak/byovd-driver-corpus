# `fse.sys`

[Назад до індексу](../README.uk.md) · [English version](fse.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3E1898007BED6FE0D8932D21A013E7826EB04F17A89F3270B66BE4351E940031` | `91EDDA5F5369E525850F6D3FFCE09BC848B067DA` | `11D99CF92024A07AC41E43F57B316D64` |

## Метадані

- **Ім'я файлу:** `fse.sys`
- **Розмір:** 230888 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Flow Steering Engine Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
