# `USBSTOR.SYS`

[Назад до індексу](../README.uk.md) · [English version](USBSTOR.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `59363B1EF2BBF72267DED60C081111D432249D2DA6EB2A21C8D238F5498ECD65` | `3080DA03FD2722A10D93A37E8DC3A0FF3B2FBCA3` | `1A943FEF92F3BABD27D68E7F9A10C6F5` |

## Метадані

- **Ім'я файлу:** `USBSTOR.SYS` (Ідентичні копії: `USBSTOR_1.SYS`)
- **Розмір:** 206304 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** USB Mass Storage Class Driver
- **Підпис:** signed
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
