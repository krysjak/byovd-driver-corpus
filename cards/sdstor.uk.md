# `sdstor.sys`

[Назад до індексу](../README.uk.md) · [English version](sdstor.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D172AA216915C5976314DD1248F5AE47CCA54A1BD5084955E4F6640A111F6807` | `2609D99E5CAB548C99E9442001B134916D49DF77` | `A80EEE7632EBB394EEE37095DF329B2A` |

## Метадані

- **Ім'я файлу:** `sdstor.sys` (Ідентичні копії: `sdstor_1.sys`)
- **Розмір:** 140792 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** SD Storage Class Driver
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
