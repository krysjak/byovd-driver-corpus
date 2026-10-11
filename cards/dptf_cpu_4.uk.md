# `dptf_cpu_4.sys`

[Назад до індексу](../README.uk.md) · [English version](dptf_cpu_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AA131BD7B521584EDF37012A79DF17BD5FAA97082BE89A94EEC1D80CE36B3D01` | `1959883967D16F0A0497682A82DA4EA3F7FA3E77` | `C962ECC5FD8B4A3D3FD8949B8A26E8F3` |

## Метадані

- **Ім'я файлу:** `dptf_cpu_4.sys`
- **Розмір:** 71000 bytes
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
