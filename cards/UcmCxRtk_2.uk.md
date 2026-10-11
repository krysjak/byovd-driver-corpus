# `UcmCxRtk_2.sys`

[Назад до індексу](../README.uk.md) · [English version](UcmCxRtk_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `47169342C1F0842CE76D4E6A36F4005490F106D8212C1DB87A1C3AEAA8EDD9AC` | `DF88BAA5216FFA6556843AA0194F358643017A38` | `800C3AC126CD405FC454CEDA08957427` |

## Метадані

- **Ім'я файлу:** `UcmCxRtk_2.sys` (Ідентичні копії: `UcmCxRtk_3.sys`)
- **Розмір:** 89032 bytes
- **Архітектура:** 0x8664
- **Компанія:** Realtek Semiconductor Corp.
- **Продукт:** Realtek Semiconductor Corp.
- **Опис:** USB Connector Manager Realtek UCSI Client
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
