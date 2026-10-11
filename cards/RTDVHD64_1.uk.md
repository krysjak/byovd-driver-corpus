# `RTDVHD64_1.sys`

[Назад до індексу](../README.uk.md) · [English version](RTDVHD64_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3B60A5D2A9485079BCD33F6906B410EA4377ECF3FD9385A22D38D2DBEBFF9B85` | `00B396367609D735A1105CE4EB6CF95B2873F310` | `561E2397C1F6B7DD01D95D1A7AF22BD3` |

## Метадані

- **Ім'я файлу:** `RTDVHD64_1.sys`
- **Розмір:** 2191832 bytes
- **Архітектура:** 0x8664
- **Компанія:** Realtek Semiconductor Corp.
- **Продукт:** Realtek(r) High Definition Audio Function Driver
- **Опис:** Realtek(r) High Definition Audio Function Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 80

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
