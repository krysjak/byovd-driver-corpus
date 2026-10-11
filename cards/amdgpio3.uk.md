# `amdgpio3.sys`

[Назад до індексу](../README.uk.md) · [English version](amdgpio3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3D5EDA5DC49154B2605201D24E70A231A72087DD78521868E5F8D3014E4B5164` | `6F8B8F54ED3E437668CEBC878D49117F55F41319` | `6E466AF1AC4443EEE7EC8DFCCAD171A6` |

## Метадані

- **Ім'я файлу:** `amdgpio3.sys` (Ідентичні копії: `amdgpio3_1.sys`, `amdgpio3_2.sys`)
- **Розмір:** 33592 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc
- **Продукт:** AMD GPIO Controller Driver
- **Опис:** AMD GPIO Driver
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
