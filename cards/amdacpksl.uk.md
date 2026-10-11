# `amdacpksl.sys`

[Назад до індексу](../README.uk.md) · [English version](amdacpksl.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F715A444805E855C2E8423387CE1D1E9234B379197690F8E9A47313B41A8C646` | `FFECDA4F9F8DC37D9EBDF63A86BF68226F94CF44` | `0E12C42DDB639C044BE1BD951381F8B3` |

## Метадані

- **Ім'я файлу:** `amdacpksl.sys`
- **Розмір:** 354096 bytes
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
