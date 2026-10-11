# `dptf_acpi_5.sys`

[Назад до індексу](../README.uk.md) · [English version](dptf_acpi_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BFDF94D9DD45F9E0396BC27E19A44D02A95F26E1754311CA15327ADBA95ADCFA` | `7C426E24403F007F679E164F6DA407BC87C85A2F` | `A442E9D0F9F3D3064D4C064BEEFA866C` |

## Метадані

- **Ім'я файлу:** `dptf_acpi_5.sys`
- **Розмір:** 74584 bytes
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
