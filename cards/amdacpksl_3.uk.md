# `amdacpksl_3.sys`

[Назад до індексу](../README.uk.md) · [English version](amdacpksl_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F895362D518829FD0B209B93C2D8A44000C8D7A450232DE37DAFEAD6A760D199` | `54495B6B4B0D8B37659A442097B5F0043BA71BEC` | `8BFFFD9ECA702B2DBC5E77D4FEEC43C8` |

## Метадані

- **Ім'я файлу:** `amdacpksl_3.sys`
- **Розмір:** 354056 bytes
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
