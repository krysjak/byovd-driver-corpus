# `netcxrd.sys`

[Назад до індексу](../README.uk.md) · [English version](netcxrd.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FD12CB90A7813BC4BDE0113AC9888014A2F05F8ED44FEA9A7769DDF203D5B04F` | `F5AD3B57A441AC73BF13044817E3A11936FCF676` | `EB8400DB8C49DF560A154E06BB4CFFB5` |

## Метадані

- **Ім'я файлу:** `netcxrd.sys`
- **Розмір:** 294912 bytes
- **Архітектура:** 0x8664
- **Компанія:** —
- **Продукт:** —
- **Опис:** —
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`, `process handle access`, `process termination`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`, `ZwOpenProcess`, `ZwTerminateProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
