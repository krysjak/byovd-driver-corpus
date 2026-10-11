# `i3chost_1.sys`

[Назад до індексу](../README.uk.md) · [English version](i3chost_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0898003C7B9E0AD574471DCD3FD8B1BC5808088C9E5AB9875D0A93D1CBEA2A4F` | `0FDA3DFFD365C1AFD206BDF8B93361A0D01F2F5D` | `C77A68CEB92C040303398601D8A625CC` |

## Метадані

- **Ім'я файлу:** `i3chost_1.sys` (Ідентичні копії: `i3chost_2.sys`)
- **Розмір:** 452048 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** I3C HostController Driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Live system
- **Score:** 65

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
