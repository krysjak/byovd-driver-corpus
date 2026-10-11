# `TeeDriverW8x64_4.sys`

[Назад до індексу](../README.uk.md) · [English version](TeeDriverW8x64_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4E997005F7663302F2100FECCF204D5C0E202A8328B6368C396A10DDA7FFEAF9` | `A290DF30A2D330E69728898B3D6C3AC4B3371EA4` | `A0B73E11C63EC6E194AACD606EAF01B9` |

## Метадані

- **Ім'я файлу:** `TeeDriverW8x64_4.sys`
- **Розмір:** 266128 bytes
- **Архітектура:** 0x8664
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
