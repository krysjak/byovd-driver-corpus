# `UcmCxRtk.sys`

[Назад до індексу](../README.uk.md) · [English version](UcmCxRtk.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `236B7CEBAAFF464C7EE5780A9A8669BB07B473DA06A1B07904E7A54FFC054271` | `C22037874EEC3F8F752D218710E2F14DF0C47D6C` | `7677DD03C226BE9B8EA2B21F881084FE` |

## Метадані

- **Ім'я файлу:** `UcmCxRtk.sys` (Ідентичні копії: `UcmCxRtk_1.sys`)
- **Розмір:** 89128 bytes
- **Архітектура:** 0x8664
- **Компанія:** Realtek Semiconductor Corp.
- **Продукт:** Realtek Semiconductor Corp.
- **Опис:** USB Connector Manager Realtek UCSI Client
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
