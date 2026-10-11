# `TeeDriverW8_3.sys`

[Назад до індексу](../README.uk.md) · [English version](TeeDriverW8_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B99689BE1615C0B81D10EDEB5FE335D716AC877F38E340987F31581D2C40F861` | `EDD008AE71D065C07E994B9062233DE0F09D231D` | `3CA4964A7446701B073A13B3C70268F7` |

## Метадані

- **Ім'я файлу:** `TeeDriverW8_3.sys`
- **Розмір:** 178336 bytes
- **Архітектура:** 0x14c
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 70

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
