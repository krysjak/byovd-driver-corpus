# `vmx86.sys`

[Назад до індексу](../README.uk.md) · [English version](vmx86.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4BFB88A5EBCC36A1D7C45F5B4D51BDC44BBB42179ACD023B35EE8BA87ECD9543` | `7DBB9E8284C5FD2F8EC771C84AC0422B47BD0C99` | `EF15D6C224D31A39A0D39E6C5CDCAF45` |

## Метадані

- **Ім'я файлу:** `vmx86.sys`
- **Розмір:** 100920 bytes
- **Архітектура:** 0x8664
- **Компанія:** Broadcom Inc.
- **Продукт:** VMware kernel driver
- **Опис:** VMware kernel driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`, `ZwMapViewOfSection`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
