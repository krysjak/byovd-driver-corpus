# `amdgpio2_4.sys`

[Назад до індексу](../README.uk.md) · [English version](amdgpio2_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8AE3E0D6D00933D6591CDD42EFFCB4F1A8706A81768768F0CAD187BB778D5AD1` | `5BD96F22A0CE3621CB8DE85F28E42FFFEF35F64E` | `3709E9F627E5BFD231869E735F93E78B` |

## Метадані

- **Ім'я файлу:** `amdgpio2_4.sys`
- **Розмір:** 56024 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc
- **Продукт:** AMD GPIO Controller Driver
- **Опис:** AMD GPIO Controller Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
