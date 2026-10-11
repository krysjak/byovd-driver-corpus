# `ST_Accel_4.sys`

[Назад до індексу](../README.uk.md) · [English version](ST_Accel_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B24D34D6076E397F688C76699B0977E9E3FC148392C3DE1077F4A5578902CD65` | `31806EF21A8EBC319EC5E41D963E366751B615D1` | `3EB4DF46F1BE48957AA96AF34D0DE6D5` |

## Метадані

- **Ім'я файлу:** `ST_Accel_4.sys`
- **Розмір:** 137784 bytes
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
