# `intelppm_1.sys`

[Назад до індексу](../README.uk.md) · [English version](intelppm_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `37D2043835FA4A57C672B9383A0A0E73E596BBE3730BCA176BA7B15299C3C1E2` | `4D2CFAB700D2DA7C167F45C629A569B95F1BBA75` | `6458AECD43DF66C6F88D6029F7F6FF2B` |

## Метадані

- **Ім'я файлу:** `intelppm_1.sys` (Ідентичні копії: `intelppm_3.sys`)
- **Розмір:** 300432 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Processor Device Driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
