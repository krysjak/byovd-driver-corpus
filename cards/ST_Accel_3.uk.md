# `ST_Accel_3.sys`

[Назад до індексу](../README.uk.md) · [English version](ST_Accel_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0BA077EBA6DCBB412CE3D2F6C951A025EE70AE711B881593EA1531F4CBE7EA9A` | `24A7641C0FF6F072208D6DD5F6DCA5C2EFEBC506` | `9E13A95627D802AD9F941ADBF52E2B54` |

## Метадані

- **Ім'я файлу:** `ST_Accel_3.sys`
- **Розмір:** 115768 bytes
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
