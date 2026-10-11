# `dptf_cpu_1.sys`

[Назад до індексу](../README.uk.md) · [English version](dptf_cpu_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2655F74A0F4C2575F3D57662DF52704656BFAF3E1F4FAE7443797EE70889D5AE` | `1F098862AE638D55B843988E32E71010EEBC6215` | `5F9B9A1A929E047236B4A6F637A8E7BC` |

## Метадані

- **Ім'я файлу:** `dptf_cpu_1.sys`
- **Розмір:** 70568 bytes
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
