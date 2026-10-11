# `amdfendr_3.sys`

[Назад до індексу](../README.uk.md) · [English version](amdfendr_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `922ADDF96DF6F28DFB66504F332FF31A219F4C8A237DDDC6E0A9386ABE09A20F` | `C46DF63C3E2727EA2FD5EC6460BACD56B9C894FC` | `46B8FE6E27D744739080CAD4F6A6AE16` |

## Метадані

- **Ім'я файлу:** `amdfendr_3.sys`
- **Розмір:** 165848 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc.
- **Продукт:** AMD Driver
- **Опис:** AMD Crash Defender
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
