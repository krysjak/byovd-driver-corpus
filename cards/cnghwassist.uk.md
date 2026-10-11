# `cnghwassist.sys`

[Назад до індексу](../README.uk.md) · [English version](cnghwassist.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8D79879E02F6DC19F04743D78004E228D3EBF64A5CC3A57D0E0B624091BE5765` | `6165749C0EEEDEA854FF473D0477E6E5A7687A05` | `3E4D2BAEFC5BEFD32EA3923BCB96BFBF` |

## Метадані

- **Ім'я файлу:** `cnghwassist.sys`
- **Розмір:** 75056 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** CNG Hardware Assist algorithm provider
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
