# `IntelTACD.sys`

[Назад до індексу](../README.uk.md) · [English version](IntelTACD.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `27E3DF3778E939D5FBFBC0428A6EF60516B7EAEB555ECC0A97833C7E37A09882` | `DE8FA9CF347EE6DCD5FC63EEEE359C35B42F7F03` | `22ECBDE59F8A5901D29BBBCB54979E7E` |

## Метадані

- **Ім'я файлу:** `IntelTACD.sys`
- **Розмір:** 59952 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel Telemetry Aggregator Consumer Driver
- **Опис:** Intel Telemetry Aggregator Consumer Driver 
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
