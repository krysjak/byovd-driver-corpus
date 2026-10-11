# `cimfs.sys`

[Назад до індексу](../README.uk.md) · [English version](cimfs.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `42E8EE5DDC96E68F4A3C7C1346D289F0720F4ADB03DAC4700998A76F475A13E7` | `C8A1407A56C697AAEE3A136288D1DCFBBEABB581` | `9002CF695B573C4C28623B087C44C550` |

## Метадані

- **Ім'я файлу:** `cimfs.sys`
- **Розмір:** 284144 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** CimFS driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
