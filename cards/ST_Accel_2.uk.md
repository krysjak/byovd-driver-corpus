# `ST_Accel_2.sys`

[Назад до індексу](../README.uk.md) · [English version](ST_Accel_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `57D6E98B766C8707C89D3220A8425CBFC08406F80D66966A55EBB1F602CD47E2` | `4ECB05D0A4926D3AF500B0A25B71A7BADF873A82` | `BD335EA8DB8DE109A32761E80B94771B` |

## Метадані

- **Ім'я файлу:** `ST_Accel_2.sys`
- **Розмір:** 275216 bytes
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
