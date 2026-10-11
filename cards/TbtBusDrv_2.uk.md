# `TbtBusDrv_2.sys`

[Назад до індексу](../README.uk.md) · [English version](TbtBusDrv_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C348F340DC60EEC244842E44354B6FB9A1D867CB1F5B860929954140F9A38522` | `7066826B8AD9BADBAD4E4214B4987B303CCC46F5` | `87C3C457D58391E8B9967CB9DBAD3D6C` |

## Метадані

- **Ім'я файлу:** `TbtBusDrv_2.sys`
- **Розмір:** 2991240 bytes
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
