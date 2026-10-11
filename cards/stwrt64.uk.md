# `stwrt64.sys`

[Назад до індексу](../README.uk.md) · [English version](stwrt64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FC4B2BD03037EC07F4443BBE13A28859035F7229CA06D4E42AFB42ABF1A89F09` | `8E0C5F83DA0C4981B31A704A73A74D00ED0DC3CC` | `71CB3BB20F08BB724769DAAAFD5AB26E` |

## Метадані

- **Ім'я файлу:** `stwrt64.sys`
- **Розмір:** 551936 bytes
- **Архітектура:** 0x8664
- **Компанія:** IDT, Inc.
- **Продукт:** IDT PC Audio
- **Опис:** IDT PC Audio
- **Підпис:** unsigned
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
