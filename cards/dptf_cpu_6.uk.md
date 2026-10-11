# `dptf_cpu_6.sys`

[Назад до індексу](../README.uk.md) · [English version](dptf_cpu_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `96BD79DD844404D0F7B5356F3F3783C5A90108BE1D22CCF50A768B6322DC347A` | `916AE0E8C246D9C4788215CA73B773F5579D0962` | `E7B48720252E0FE6712EDF6B9DD3500F` |

## Метадані

- **Ім'я файлу:** `dptf_cpu_6.sys`
- **Розмір:** 75248 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Dynamic Platform Thermal Framework
- **Опис:** DPTF CPU Device (64-Bit)
- **Підпис:** signed
- **Джерело:** `oem:dell`
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
