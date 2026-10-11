# `wintun.sys`

[Назад до індексу](../README.uk.md) · [English version](wintun.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1A7BB3555C5419BEFB1A5F54267DCAE9A7AF16749DDF4EEF9B431FCF0B863110` | `1E0DD7B0D0C0B880BF6864134D1E792E80E875FC` | `43D91124FE8112D0027842824DAD7326` |

## Метадані

- **Ім'я файлу:** `wintun.sys` (Ідентичні копії: `wintun_1.sys`)
- **Розмір:** 29592 bytes
- **Архітектура:** 0x8664
- **Компанія:** WireGuard LLC
- **Продукт:** Wintun Driver
- **Опис:** Wintun Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process lookup`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `PsLookupProcessByProcessId`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
