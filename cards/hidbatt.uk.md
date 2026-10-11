# `hidbatt.sys`

[Назад до індексу](../README.uk.md) · [English version](hidbatt.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `23FC4EAD8368F57CF40993491F3FE7E48D2866870EEFDCE923F78BA387830E45` | `28182A470F8333BA1C96731F0D658338A7253D74` | `AD72D2B31ADD72BB9A4EB4D2C051A09C` |

## Метадані

- **Ім'я файлу:** `hidbatt.sys` (Ідентичні копії: `hidbatt_1.sys`)
- **Розмір:** 75168 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Hid Battery Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
