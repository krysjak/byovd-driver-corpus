# `amdacpksl_7.sys`

[Назад до індексу](../README.uk.md) · [English version](amdacpksl_7.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AA0601CC0F248A6453D93AC8314AF5674017AE17E944E8AB3EEF8D13727E4C68` | `9F22E9BEF199BAADBD63206D6142EB4409B4FDDC` | `B7B4C1B05ABB20CB3907271E8068A575` |

## Метадані

- **Ім'я файлу:** `amdacpksl_7.sys`
- **Розмір:** 352864 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices
- **Продукт:** AMD KSL Filter Driver
- **Опис:** AMD KSL Filter Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
