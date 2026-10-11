# `dptf_cpu_7.sys`

[Назад до індексу](../README.uk.md) · [English version](dptf_cpu_7.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `36628984FB45C711AF6D230D4B8B565AF7E94BC3F5E5C0C3BE4D867AEC01B97D` | `415334B5F4F7FAFDB9C657740941C4971E4E72F3` | `2E034D188092D6DCAE2CC35BA326F684` |

## Метадані

- **Ім'я файлу:** `dptf_cpu_7.sys`
- **Розмір:** 74120 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Dynamic Tuning
- **Опис:** Intel(R) Dynamic Tuning CPU Participant
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
