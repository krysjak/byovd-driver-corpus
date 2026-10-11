# `dptf_acpi.sys`

[Назад до індексу](../README.uk.md) · [English version](dptf_acpi.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2092109E2EE977D43E04D02176A03196DEC5293EF34DF6D76DDAC8A6AEDB8590` | `47267C7427D9FC79973AA20D0161268D8AB38EAE` | `1D3B0FACD43CE41CA5EFC3C5EA8E51F7` |

## Метадані

- **Ім'я файлу:** `dptf_acpi.sys`
- **Розмір:** 81040 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Dynamic Tuning
- **Опис:** Intel(R) Dynamic Tuning ACPI Participant
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
