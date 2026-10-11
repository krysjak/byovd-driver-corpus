# `mlx5.sys`

[Назад до індексу](../README.uk.md) · [English version](mlx5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `453AD7F8590ADB357405D6DEEC5F868BA4B09AA351D4ABED64EAC6CF0B7754F9` | `115E6AF6AF6A8738CA15DF13344FE3770BE409DE` | `622726E4BC437E20CA689CD9F81E3D03` |

## Метадані

- **Ім'я файлу:** `mlx5.sys`
- **Розмір:** 2433440 bytes
- **Архітектура:** 0x8664
- **Компанія:** Mellanox
- **Продукт:** OpenFabrics Windows
- **Опис:** Mellanox ConnectX Adapter NDIS driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
