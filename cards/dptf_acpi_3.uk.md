# `dptf_acpi_3.sys`

[Назад до індексу](../README.uk.md) · [English version](dptf_acpi_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `406BF705E99AA2463BADD0B89F2151EB31DB66081A560E6AA0E525198AD80383` | `4330C7349E27861CEE710523EF088536DFEC266D` | `84873CD34EDAC3C2C98392EE942A695F` |

## Метадані

- **Ім'я файлу:** `dptf_acpi_3.sys`
- **Розмір:** 76952 bytes
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
