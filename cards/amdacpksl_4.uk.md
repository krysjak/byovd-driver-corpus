# `amdacpksl_4.sys`

[Назад до індексу](../README.uk.md) · [English version](amdacpksl_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6A8CFE1C7B02C2A0DED08CA0E244581C9FF85CF93D35710DFC6763CF46337B2A` | `991DF7680A8C1A01E60DB5EBEA4B9B6C956AF55F` | `B19E0240A055059D525DB2DA93790D6C` |

## Метадані

- **Ім'я файлу:** `amdacpksl_4.sys`
- **Розмір:** 353912 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices
- **Продукт:** AMD KSL Filter Driver
- **Опис:** AMD KSL Filter Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 55

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
