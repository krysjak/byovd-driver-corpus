# `TbtBusDrv_3.sys`

[Назад до індексу](../README.uk.md) · [English version](TbtBusDrv_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E7E3C3E18E928D2B7E81FC5609E1D4F20029C45E642C26EADEA6DCFF98D22C2F` | `650A2F5EC372992368533B962E67DC9DA93E618E` | `92B3681E40DE5A34688433F8C568CA66` |

## Метадані

- **Ім'я файлу:** `TbtBusDrv_3.sys`
- **Розмір:** 2552272 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Thunderbolt(TM) Bus Driver
- **Опис:** Thunderbolt(TM) Bus Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 70

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
