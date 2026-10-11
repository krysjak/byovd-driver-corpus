# `dptf_cpu_5.sys`

[Назад до індексу](../README.uk.md) · [English version](dptf_cpu_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E1E8CD148F3A0EB93F864A0AA8D9302A1DF5B9C2C5E4BFDF9C293D6FBF2282A0` | `46BB4C1E9812CC7FA50BA6CC52B9E14A4FF8DA50` | `A528415D99D3301B669E8933D7E45507` |

## Метадані

- **Ім'я файлу:** `dptf_cpu_5.sys`
- **Розмір:** 69984 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Dynamic Platform Thermal Framework
- **Опис:** DPTF CPU Device (64-Bit)
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
