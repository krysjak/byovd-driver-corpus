# `ipf_smbus.sys`

[Назад до індексу](../README.uk.md) · [English version](ipf_smbus.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `672EB5C1D67AD52586713AC80131CDF6C21DA5CB3EE9CB211AE14FAEB8F8EE83` | `38A38F8F0E1AA9AF7BCD88BAED788989422AB39A` | `F5D24E39FC4064431229EF03B6E2B572` |

## Метадані

- **Ім'я файлу:** `ipf_smbus.sys`
- **Розмір:** 73288 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Innovation Platform Framework
- **Опис:** Intel(R) Innovation Platform Framework SMBUS Driver
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
