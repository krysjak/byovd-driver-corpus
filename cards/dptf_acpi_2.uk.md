# `dptf_acpi_2.sys`

[Назад до індексу](../README.uk.md) · [English version](dptf_acpi_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9833A800C23645BAD1113D40E7B5A973721AA80E9BDDD671B3C2F210A086EB8E` | `67A12840C07322EF2C845E05A3CAFEA8DD9EE161` | `62C3DC41B595CFA91D821F64F6750580` |

## Метадані

- **Ім'я файлу:** `dptf_acpi_2.sys`
- **Розмір:** 81056 bytes
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
