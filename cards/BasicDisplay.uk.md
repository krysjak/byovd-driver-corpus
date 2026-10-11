# `BasicDisplay.sys`

[Назад до індексу](../README.uk.md) · [English version](BasicDisplay.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `75AB8FD5C899616E70B6252B6C7291463F7750DE5866FBB5B6F8B0D21DAF3EEA` | `E087422737BA5AD1B0AC553DB8CF3A241CFCE42A` | `6B90CD4EAD021F3A91D7F30F23C37275` |

## Метадані

- **Ім'я файлу:** `BasicDisplay.sys`
- **Розмір:** 106496 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft Basic Display Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `driver loading`, `physical memory mapping`, `system information set`

**Imports:** `MmMapIoSpaceEx`, `ZwLoadDriver`, `ZwSetSystemInformation`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
