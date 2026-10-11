# `rccfg.sys`

[Назад до індексу](../README.uk.md) · [English version](rccfg.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4531FB962055A8A6DBB5AC94928A77D42E71E0DD506D5C8BFB67381DFEF97276` | `7784ED0C4FF0135D129FFBCD37E385AC05B89154` | `B87470FAB5B027FDC3ECA22424935324` |

## Метадані

- **Ім'я файлу:** `rccfg.sys`
- **Розмір:** 35112 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc.
- **Продукт:** AMD-RAID Configuration driver
- **Опис:** AMD-RAID Configuration driver
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
