# `amdfendr_2.sys`

[Назад до індексу](../README.uk.md) · [English version](amdfendr_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6CC6D9CA61F86B96697D67DC373EA5FA3076AA43EC63EADFE26450F1F3E51883` | `3174825ABFF07AE084B474BFB8A3A769F85BA5F9` | `B9FA5F8958E815CA747832E09AA4C700` |

## Метадані

- **Ім'я файлу:** `amdfendr_2.sys`
- **Розмір:** 147872 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc.
- **Продукт:** AMD Driver
- **Опис:** AMD Crash Defender
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 100

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
