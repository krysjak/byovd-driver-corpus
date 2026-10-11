# `kipudrv.sys`

[Назад до індексу](../README.uk.md) · [English version](kipudrv.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1ADD63E519CE5F2D6C0CBF2EDA75BB988CEC78809D1EB3C5DDCFD86CDBA68067` | `BAE3B8A733CAAED638638DA17BD3D85F0F279EDA` | `2B3B8A3E64F5CE0DBF208EC5E5707782` |

## Метадані

- **Ім'я файлу:** `kipudrv.sys`
- **Розмір:** 832184 bytes
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
