# `amdacpksl_6.sys`

[Назад до індексу](../README.uk.md) · [English version](amdacpksl_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `45F8EA3FE64670D8512E2A5A66C8008C5A20DD698B367311CCA6AA99ACDFEE25` | `1B1151DB2E445FC1214B947B557D1D08CF4FC989` | `A308A21E111FB57DF75A08D4423D1E19` |

## Метадані

- **Ім'я файлу:** `amdacpksl_6.sys`
- **Розмір:** 353944 bytes
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
