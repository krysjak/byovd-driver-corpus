# `dptf_acpi_7.sys`

[Назад до індексу](../README.uk.md) · [English version](dptf_acpi_7.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AF97AD9F6F6D711EC59AD36BA05C80B4A79E4DEEF9E9252C7781A52FFF28ED20` | `557FF091E0B00B77A710507323D1CD00220F9B64` | `F6A4005CEB6FD7E8500D871A3B158046` |

## Метадані

- **Ім'я файлу:** `dptf_acpi_7.sys`
- **Розмір:** 77192 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Dynamic Tuning
- **Опис:** Intel(R) Dynamic Tuning ACPI Participant
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
