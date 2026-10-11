# `lxcore.sys`

[Назад до індексу](../README.uk.md) · [English version](lxcore.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `CC1E56586944C7D161B3A7AB9EBEF351A72F1820291FD1565046344CC9C4ECA4` | `A7376087C7FFCA360F62FED4FB85231B92E5589D` | `94034B4728321AB227557C935D38E8EF` |

## Метадані

- **Ім'я файлу:** `lxcore.sys`
- **Розмір:** 1127936 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** LX Core
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process termination`, `section mapping (kernel R/W surface)`, `system image loading`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmLoadSystemImage`, `MmProbeAndLockPages`, `ZwMapViewOfSection`, `ZwTerminateProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
