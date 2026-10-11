# `vmnetuserif.sys`

[Назад до індексу](../README.uk.md) · [English version](vmnetuserif.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1191DD88953DBF63EE7A51182FFC019E75D78FCB13B8790644139EF9273656E4` | `A0005477CEEFEE4C833325F90006357A4B3AE8C8` | `1BF8B1EDA63954C5C6932E41FD5AA857` |

## Метадані

- **Ім'я файлу:** `vmnetuserif.sys`
- **Розмір:** 30664 bytes
- **Архітектура:** 0x8664
- **Компанія:** Broadcom Inc.
- **Продукт:** VMware network application interface driver (64-bit)
- **Опис:** VMware network application interface driver (64-bit)
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
