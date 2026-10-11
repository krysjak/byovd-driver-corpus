# `ipf_acpi_1.sys`

[Назад до індексу](../README.uk.md) · [English version](ipf_acpi_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8A85282BAC0AE0945588506B82E74EABCC8CE924E56260D74A5C1768646421F3` | `DEAC7773C60B1B2BFDCBA628BC1602F61AE3CFA8` | `B86639187D91EE5432CA58E140B95178` |

## Метадані

- **Ім'я файлу:** `ipf_acpi_1.sys`
- **Розмір:** 85656 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Innovation Platform Framework
- **Опис:** Intel(R) Innovation Platform Framework ACPI Participant
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
