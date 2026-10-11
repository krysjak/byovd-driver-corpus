# `TeeDriverW8_5.sys`

[Назад до індексу](../README.uk.md) · [English version](TeeDriverW8_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `75DB74CCF5AD0155ABDE427DDB0D9A105B3AE5D2D1E3C1BEB7BA9FABF1ED1938` | `38F240C8FD1A56D5811459F1B518DF5CABBCD527` | `82CBD25441A46064294262132734A25D` |

## Метадані

- **Ім'я файлу:** `TeeDriverW8_5.sys`
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
