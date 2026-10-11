# `TEEDriverW8x64_7.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW8x64_7.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0BAA44DEC06C5247DC901BA4633F1CB6CB9A040B62538FF03AFD6225640B3A2A` | `D30B55D9656DA26AD40A55413CAE449FFAF80555` | `08FEE1CA16B1F1EF7B1A553A7EEAC8B9` |

## Метадані

- **Ім'я файлу:** `TEEDriverW8x64_7.sys`
- **Розмір:** 275072 bytes
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
