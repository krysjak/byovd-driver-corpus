# `dptf_acpi_6.sys`

[Назад до індексу](../README.uk.md) · [English version](dptf_acpi_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `88AE72128DB834045ED915B84DEE22789B6A123F5E1051E6657BD53C2E9E2C56` | `E40903250FC2224D24FAC0F9AC6A71FA15F1F5F6` | `120D80CB775D1FCD02E615E3206731FE` |

## Метадані

- **Ім'я файлу:** `dptf_acpi_6.sys`
- **Розмір:** 78832 bytes
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
