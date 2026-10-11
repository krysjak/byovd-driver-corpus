# `amdacpksl_5.sys`

[Назад до індексу](../README.uk.md) · [English version](amdacpksl_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D84172E7CA3228570FA9AF29E64F21D4BEFBFE37BD77DD1A9F1FFDE79F83C00C` | `FBCD50D8E3D5E4FE97D42A4923C19A927BEA0994` | `994547FF892153AF34285C0BC068444B` |

## Метадані

- **Ім'я файлу:** `amdacpksl_5.sys`
- **Розмір:** 352880 bytes
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
