# `dptf_acpi_4.sys`

[Назад до індексу](../README.uk.md) · [English version](dptf_acpi_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0203F6844FDEC4EAA31D0F8441E2E0BE07F9B7CF55155ADDD15CF52008BDDE2B` | `7B7D4A327E63AEC6DB2438ABEFE39A1CB1AE854F` | `156225CAEDCA4722C14217CEA3EE0EF7` |

## Метадані

- **Ім'я файлу:** `dptf_acpi_4.sys`
- **Розмір:** 78680 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Dynamic Platform Thermal Framework
- **Опис:** DPTF ACPI Device (64-Bit)
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
