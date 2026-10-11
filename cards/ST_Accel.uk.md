# `ST_Accel.sys`

[Назад до індексу](../README.uk.md) · [English version](ST_Accel.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2098B2F4E012A74A5D7A9A2AA1D6DBD2E10B4DA4461F6C15881263D3508E17BB` | `7D4F0C34FBB6CC9CF14AB06AD7CFF9F488A0E5F8` | `C81FF7B2EC243657D98CAE93984D5EC9` |

## Метадані

- **Ім'я файлу:** `ST_Accel.sys`
- **Розмір:** 75392 bytes
- **Архітектура:** 0x14c
- **Компанія:** STMicroelectronics
- **Продукт:** STM 3-Axis Accelerometer
- **Опис:** STM Accelerometer Device Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `contiguous physical allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
