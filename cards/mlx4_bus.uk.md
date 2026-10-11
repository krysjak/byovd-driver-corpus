# `mlx4_bus.sys`

[Назад до індексу](../README.uk.md) · [English version](mlx4_bus.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `211BDC6BB0720EE7221D77F205BD828AB4172AC4F454877BEAF5E3D74419442C` | `640189825BA80D7E2DF6F09351626CA276ACF2A0` | `1C652F46B0E067E856632651CC394863` |

## Метадані

- **Ім'я файлу:** `mlx4_bus.sys` (Ідентичні копії: `mlx4_bus_1.sys`)
- **Розмір:** 1132336 bytes
- **Архітектура:** 0x8664
- **Компанія:** Mellanox
- **Продукт:** OpenFabrics Windows
- **Опис:** MLX4 Bus Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
