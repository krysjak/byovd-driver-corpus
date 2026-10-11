# `ipf_cpu.sys`

[Назад до індексу](../README.uk.md) · [English version](ipf_cpu.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D104C6F2E9EFCC92B4D01BB3E826505618CA868E60E54195D8A48450CC6DE540` | `5F167FB144E980ECA15A6D00CAD27D924FBC51BC` | `F3F28DD1CD24D4A29DA3058D46A498D4` |

## Метадані

- **Ім'я файлу:** `ipf_cpu.sys`
- **Розмір:** 89672 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Innovation Platform Framework
- **Опис:** Intel(R) Innovation Platform Framework CPU Participant
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
