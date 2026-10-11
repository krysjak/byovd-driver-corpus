# `amdgpio2_3.sys`

[Назад до індексу](../README.uk.md) · [English version](amdgpio2_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `46A53925BAA34FA9D87E7C3157504A4557D81CD8B8608E7AB6CAF02F482F7792` | `7A8D676BC87AED25822F303C7F2E2286FBAC5BBA` | `55578CF027B0AE9F0D653B209C9F1B6D` |

## Метадані

- **Ім'я файлу:** `amdgpio2_3.sys` (Ідентичні копії: `amdgpio2_5.sys`)
- **Розмір:** 18432 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc
- **Продукт:** AMD GPIO Controller Driver
- **Опис:** AMD GPIO Controller Driver
- **Підпис:** unsigned
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 55

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
