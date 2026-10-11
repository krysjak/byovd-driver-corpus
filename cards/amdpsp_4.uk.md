# `amdpsp_4.sys`

[Назад до індексу](../README.uk.md) · [English version](amdpsp_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AA09BAF79AE92424ABC96E42D1F30DD0A60DA62CB9091BD4BC74F36AEEDF932F` | `2CB17A5A474C66F5CE2A68D7C03CF7399874D86E` | `8954D35CAF3A6E37C6DE8F90A883E288` |

## Метадані

- **Ім'я файлу:** `amdpsp_4.sys`
- **Розмір:** 52656 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc. 
- **Продукт:** Advanced Micro Devices, Inc. amdpsp sys
- **Опис:** amdpsp sys
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
