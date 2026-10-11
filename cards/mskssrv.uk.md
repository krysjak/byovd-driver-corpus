# `mskssrv.sys`

[Назад до індексу](../README.uk.md) · [English version](mskssrv.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9C0E1552EA6EA826CFB709781FEC95E08195698B7881A2DD7A96590D5DFE88A5` | `4A7170CD8D7DD041CF56D755B09D4B389409D9B6` | `530C41B7BDD1A185E88F8926A2B4D93F` |

## Метадані

- **Ім'я файлу:** `mskssrv.sys`
- **Розмір:** 77824 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** MS KS Server
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
