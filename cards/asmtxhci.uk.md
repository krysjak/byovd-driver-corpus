# `asmtxhci.sys`

[Назад до індексу](../README.uk.md) · [English version](asmtxhci.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `03008CC5FB2446C08DEA0EE1BA79F34D3C933600F2B77705B5C94AAB47496355` | `CEFDDE53E7B6B9B62D21CCD6444C71F5036F8498` | `E982C13AE03192528C52FAF1B3A4ACB7` |

## Метадані

- **Ім'я файлу:** `asmtxhci.sys`
- **Розмір:** 483504 bytes
- **Архітектура:** 0x8664
- **Компанія:** ASMedia Technology Inc
- **Продукт:** ASMedia USB 3.1 Host Drivers
- **Опис:** ASMedia xHCI Host Controller Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 110

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
