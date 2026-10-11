# `TeeDriverW8_4.sys`

[Назад до індексу](../README.uk.md) · [English version](TeeDriverW8_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9D217C8F93FAFEBBB911B870B37D2293311D3CC945830100C4720823ADF8A052` | `BC66E45125A158504803A804EA300417D9A2716B` | `73D3701BC83297142086385B6A4B8E26` |

## Метадані

- **Ім'я файлу:** `TeeDriverW8_4.sys`
- **Розмір:** 233872 bytes
- **Архітектура:** 0x14c
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
