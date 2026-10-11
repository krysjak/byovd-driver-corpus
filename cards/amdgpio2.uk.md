# `amdgpio2.sys`

[Назад до індексу](../README.uk.md) · [English version](amdgpio2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `93DC48E60476F5D4DC456657387EF46E38D5E705F51B55543F044AA2F1E9E0F6` | `F518837135F8AC61919FA23D89BD54B31D67460D` | `3CFE13542AEE43E026DCBDAC0B556CFC` |

## Метадані

- **Ім'я файлу:** `amdgpio2.sys` (Ідентичні копії: `amdgpio2_1.sys`, `amdgpio2_2.sys`)
- **Розмір:** 53064 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc
- **Продукт:** AMD GPIO Controller Driver
- **Опис:** AMD GPIO Controller Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
