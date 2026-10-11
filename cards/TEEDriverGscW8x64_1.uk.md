# `TEEDriverGscW8x64_1.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverGscW8x64_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F45AF79006486102343130CFC6A1C0EF441942F1ABC85C591E25FE62302F847B` | `6ADC7B88672C5B0871BF0255F5DEABD9C71AC431` | `0A45ECC24C27EBDFED12EAB0B95E6A5D` |

## Метадані

- **Ім'я файлу:** `TEEDriverGscW8x64_1.sys`
- **Розмір:** 259824 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
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
