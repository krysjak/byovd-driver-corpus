# `refs.sys`

[Назад до індексу](../README.uk.md) · [English version](refs.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5C92FC9181B31980E04D96A14C56925C45F7ACF6D90E3E2E00750D4DFFA119BA` | `518BE8E606DC383B10C9D616948420A11C26FBB9` | `4FE0FF494A0BF08119BE4A135066FF4B` |

## Метадані

- **Ім'я файлу:** `refs.sys`
- **Розмір:** 3528168 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** NT ReFS FS Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `process lookup`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`, `ZwLoadDriver`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
