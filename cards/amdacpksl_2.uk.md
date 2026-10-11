# `amdacpksl_2.sys`

[Назад до індексу](../README.uk.md) · [English version](amdacpksl_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1B34BAC6B83DF376A4BE3A1952456C027D6A5FA182FEFD8E817562D879126560` | `13E4877D6CD886A4E63B4A67171D78EE06228D06` | `A139F621C5BB4CFF975E87995ED30CBF` |

## Метадані

- **Ім'я файлу:** `amdacpksl_2.sys`
- **Розмір:** 352864 bytes
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
