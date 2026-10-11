# `physX64.sys`

[Назад до індексу](../README.uk.md) · [English version](physX64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DA3C4D837D873085531337A99484115563ACE01A5A1085A3C0160582B480034F` | `180FC3844BE7703CF0635D1AFBE78DE71C0DB72B` | `7C0B34E30F62110CCEBC2F09BF79869C` |

## Метадані

- **Ім'я файлу:** `physX64.sys`
- **Розмір:** 148768 bytes
- **Архітектура:** 0x8664
- **Компанія:** AGEIA Technologies, Inc.
- **Продукт:** AGEIA PhysX Processor WDM Driver
- **Опис:** AGEIA PhysX Processor WDM Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
