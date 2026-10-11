# `amdpmf.sys`

[Назад до індексу](../README.uk.md) · [English version](amdpmf.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3B877B4AB3862A4D700605043501EC04E1A5CDA3595156F4C3BF36815E9FB04C` | `17CB4DE82A365B704D0FF6553A43FE3ED56CC4AA` | `926AF88B5FCF8DE8BD56BEBBC1B77FA8` |

## Метадані

- **Ім'я файлу:** `amdpmf.sys`
- **Розмір:** 202136 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc.
- **Продукт:** AMD PMF Device Driver
- **Опис:** AMD PMF Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
