# `BvWinFsp.sys`

[Назад до індексу](../README.uk.md) · [English version](BvWinFsp.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1C177E0EE8C16D44B79A8A87BA0431F41808D2003533F2576AB5E0633C42B900` | `89698FCFFAD8550C011097D254CF4FF962689BD6` | `F5217D7A646A91B1B07DB9BF5F072AC5` |

## Метадані

- **Ім'я файлу:** `BvWinFsp.sys`
- **Розмір:** 168512 bytes
- **Архітектура:** 0x8664
- **Компанія:** Navimatics LLC
- **Продукт:** WinFsp
- **Опис:** Windows File System Proxy
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwLoadDriver`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
