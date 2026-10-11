# `TEEDriverW10x64.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW10x64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `37BDFD478D64A53975452970AF44A88053206EFB2CF30D505E60E62BB383FD96` | `86C9685955FF6CC150E62C640EE83A695B6EC455` | `9DAAE14E013F21B67A51F5A275B6FBFC` |

## Метадані

- **Ім'я файлу:** `TEEDriverW10x64.sys`
- **Розмір:** 326144 bytes
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
