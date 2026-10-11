# `CmgFFE_1.sys`

[Назад до індексу](../README.uk.md) · [English version](CmgFFE_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `29867E7044AB9C85C4AB99CB49DADFB8E40321873D4A25C8FBAEF8D368797DA2` | `14F3B912E512ABB0F3D4681C154E85F3E715209B` | `79555506F700F489B4D9276540ED67F5` |

## Метадані

- **Ім'я файлу:** `CmgFFE_1.sys`
- **Розмір:** 476384 bytes
- **Архітектура:** 0x8664
- **Компанія:** Dell Inc.
- **Продукт:** Dell Data Protection Encryption
- **Опис:** Credant File & Folder Encryption Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 55

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
