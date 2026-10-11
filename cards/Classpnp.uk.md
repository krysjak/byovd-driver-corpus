# `Classpnp.sys`

[Назад до індексу](../README.uk.md) · [English version](Classpnp.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D20BABA4F0D709893F30E212DF4E15F224F84B7E1AE08F4BE734660107BB2732` | `78E6F5E0B00816AC23966FF41EB4CEF4EBCFC06C` | `E7D810658448A05AAF91700A236B186F` |

## Метадані

- **Ім'я файлу:** `Classpnp.sys`
- **Розмір:** 505304 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** SCSI Class System Dll
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
