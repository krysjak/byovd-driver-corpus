# `WdNisDrv_1.sys`

[Назад до індексу](../README.uk.md) · [English version](WdNisDrv_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `36E15C5A2A0F2F28E4DDF4AAE9455F184A26CD47CA94DDE13D76E9A0BDF7D17E` | `73CC2C40A8FFDE1EA6C4C26002495DD8D06D7C2D` | `8CBE7DF54ED48B91B673A03C909C88AA` |

## Метадані

- **Ім'я файлу:** `WdNisDrv_1.sys` (Ідентичні копії: `WdNisDrv_2.sys`)
- **Розмір:** 102816 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Windows Defender Network Stream Filter
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 70

## Профіль можливостей

**Primitives:** `MDL allocation`, `process lookup`

**Imports:** `IoAllocateMdl`, `PsLookupProcessByProcessId`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
