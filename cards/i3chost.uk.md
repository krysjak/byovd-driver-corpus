# `i3chost.sys`

[Назад до індексу](../README.uk.md) · [English version](i3chost.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `660DB171800A2848BBDFB8677911A3D2BB695F17F87D84E17BD8E85DA5501559` | `C7BB4CF27AE5A91E3D4FFF64219F495B181264EE` | `338F57B995812D19CFC571697CEE5A71` |

## Метадані

- **Ім'я файлу:** `i3chost.sys`
- **Розмір:** 349592 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** I3C HostController Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
