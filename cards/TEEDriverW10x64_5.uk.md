# `TEEDriverW10x64_5.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW10x64_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9E5950DFAFB611D332C331AB8B7688B55945F00D07F63154C5950625C5ED67BA` | `D6A796E80F701A13A53EDD75C431642D2FABF878` | `6384B088DDD97358109821DE76813584` |

## Метадані

- **Ім'я файлу:** `TEEDriverW10x64_5.sys`
- **Розмір:** 318096 bytes
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
