# `netcxrd_1.sys`

[Назад до індексу](../README.uk.md) · [English version](netcxrd_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BD1198516A5576AF702DCD833E0EE3F3AA72425A62DAE755C3D1FB126649D0F7` | `0C491663B1310F5804A462FC48E91B4E8CF6CBED` | `EEDD323D67CA8D3B1CF45BD50052DA3C` |

## Метадані

- **Ім'я файлу:** `netcxrd_1.sys` (Ідентичні копії: `netcxrd_2.sys`)
- **Розмір:** 331776 bytes
- **Архітектура:** 0x8664
- **Компанія:** —
- **Продукт:** —
- **Опис:** —
- **Підпис:** unsigned
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Live system
- **Score:** 60

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process handle access`, `process termination`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwOpenProcess`, `ZwTerminateProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
