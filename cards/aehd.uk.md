# `aehd.sys`

[Назад до індексу](../README.uk.md) · [English version](aehd.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `03E0F9FA171608F25C05C7DF9BC8AB717B02F037630EFA10FF53113F88AFE468` | `C50CA95DF00CF18CE868F6D895C68CD05810BE01` | `794D52BCF97AB8A78EBC7758090AB97E` |

## Метадані

- **Ім'я файлу:** `aehd.sys`
- **Розмір:** 403080 bytes
- **Архітектура:** 0x8664
- **Компанія:** Google LLC
- **Продукт:** Android Emulator hypervisor driver
- **Опис:** Android Emulator hypervisor driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `page locking`, `physical address resolution`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
