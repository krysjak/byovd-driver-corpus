# `rdyboost.sys`

[Назад до індексу](../README.uk.md) · [English version](rdyboost.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E83D146702F22E6A8FDB19B2F90ED7E745DCC3BCAE1FDC7F8AC8847A793AD2C1` | `B625D7AB187082D979CA6BC9B0D338090BCD6893` | `873694018375002888A61412CC019C1A` |

## Метадані

- **Ім'я файлу:** `rdyboost.sys`
- **Розмір:** 316824 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** ReadyBoost Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `process address-space attach`, `system information set`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`, `ZwSetSystemInformation`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
