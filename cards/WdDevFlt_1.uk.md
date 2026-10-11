# `WdDevFlt_1.sys`

[Назад до індексу](../README.uk.md) · [English version](WdDevFlt_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6AC5D8D09A13DE50D96E7E49DED116E0831AB0E0A39495276A3BEEE5B45BB63B` | `76F56FA0301E28B050E9A3FC024BBE4AF84B26BC` | `A8EF466AB44B930A7CA5B70B9B5E2DEF` |

## Метадані

- **Ім'я файлу:** `WdDevFlt_1.sys` (Ідентичні копії: `WdDevFlt_2.sys`)
- **Розмір:** 283016 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft antimalware device filter driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Live system
- **Score:** 55

## Профіль можливостей

**Primitives:** `process handle access`, `process lookup`

**Imports:** `PsLookupProcessByProcessId`, `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
