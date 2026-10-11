# `ST_Accel_1.sys`

[Назад до індексу](../README.uk.md) · [English version](ST_Accel_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `ABDC532B650FB02FB68EA1AB4165CBAC659369751EFE89F18937B1E88A793D07` | `749A32EF49C8185752CEAF97FA22D6307EF19C76` | `C6092EE49DCCB13C325A04A54A3318A6` |

## Метадані

- **Ім'я файлу:** `ST_Accel_1.sys`
- **Розмір:** 93432 bytes
- **Архітектура:** 0x8664
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
