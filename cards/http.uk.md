# `http.sys`

[Назад до індексу](../README.uk.md) · [English version](http.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8243270DEA941218FA6A9F3C294602BCA030935402397A435563304B5F8DD60A` | `AA8F7E435B8C539AA6CB06B161445E8B3C1926B5` | `CFB726347437FC4654881183BD850A26` |

## Метадані

- **Ім'я файлу:** `http.sys`
- **Розмір:** 2184688 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** HTTP Protocol Stack
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
