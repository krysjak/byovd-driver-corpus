# `stwrt.sys`

[Назад до індексу](../README.uk.md) · [English version](stwrt.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DDFC33C46D27701025C4EF0A14ED500AAE3C42AB115BCBE36A69234AD120589C` | `D21905763B5C2710C755272392BF3C56BA091751` | `506297253A7542476EDED5EF785C92A4` |

## Метадані

- **Ім'я файлу:** `stwrt.sys`
- **Розмір:** 459264 bytes
- **Архітектура:** 0x14c
- **Компанія:** IDT, Inc.
- **Продукт:** IDT PC Audio
- **Опис:** IDT PC Audio
- **Підпис:** unsigned
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
