# `TEEDriverW10_1.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW10_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `989AEB25857EF54F535A71D8AADBCC1547707384D93F0F01A3E076869F4FC900` | `E13D7D8BD71DF35785A4A3179ED5CA5986BDB96F` | `7FDD183367DB85FBF53B213606238816` |

## Метадані

- **Ім'я файлу:** `TEEDriverW10_1.sys`
- **Розмір:** 272864 bytes
- **Архітектура:** 0x14c
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
