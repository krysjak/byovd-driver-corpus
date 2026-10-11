# `kipudrv_win10.sys`

[Назад до індексу](../README.uk.md) · [English version](kipudrv_win10.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B5B26BE2BDE2FE31804F4493D483CA8B316081814D67961FBB8BC687E95721CE` | `EF9684DE1891BB43C178FD003AC6867C33907FC6` | `3075BF488B3C5B695DA155B20AE6B8A9` |

## Метадані

- **Ім'я файлу:** `kipudrv_win10.sys`
- **Розмір:** 828520 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc
- **Продукт:** AMD IPU Driver
- **Опис:** AMD IPU Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 80

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
