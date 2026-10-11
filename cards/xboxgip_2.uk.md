# `xboxgip_2.sys`

[Назад до індексу](../README.uk.md) · [English version](xboxgip_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4A2A28408F3E13D7C7DB4B0B4A8B2BE445FECF038F9D98F40A5B12F7FDBFCF25` | `611430989F9A2F8B3B03C70B624CBBA413D020C9` | `7D4EEFE811830A781DF5627CE175CEC2` |

## Метадані

- **Ім'я файлу:** `xboxgip_2.sys` (Ідентичні копії: `xboxgip_3.sys`)
- **Розмір:** 417792 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Game Input Protocol Driver
- **Підпис:** unsigned
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 55

## Профіль можливостей

**Primitives:** `process handle access`

**Imports:** `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
