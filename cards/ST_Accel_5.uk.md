# `ST_Accel_5.sys`

[Назад до індексу](../README.uk.md) · [English version](ST_Accel_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `855E9D5B35BDF88F38AEC024AE3E6C0AE94CC4834EA8335178C7A8A0FDC20A1A` | `1537302597A926F1AC1A64A74C2C23033E7B6C57` | `DB880C094DCC4EFD0E7E45AE8C5B2F05` |

## Метадані

- **Ім'я файлу:** `ST_Accel_5.sys`
- **Розмір:** 271928 bytes
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
