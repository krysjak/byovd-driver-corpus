# `TbtBusDrv_1.sys`

[Назад до індексу](../README.uk.md) · [English version](TbtBusDrv_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `574E2C5A35E297BB0F2046526771A432D814B69930D3F0ED43EFBBDF4CD9AEB8` | `CB84E0AD8F5F9FCC835D6E62A9811E5EE37D542A` | `49350F6DCCBA652E8E7F052F311F94AD` |

## Метадані

- **Ім'я файлу:** `TbtBusDrv_1.sys`
- **Розмір:** 3267320 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Thunderbolt(TM) Bus Driver
- **Опис:** Thunderbolt(TM) Bus Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 100

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
