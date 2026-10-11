# `TeeDriverW8_6.sys`

[Назад до індексу](../README.uk.md) · [English version](TeeDriverW8_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3F7E630EAAF986743A99FA38B725BD68A012D4D47EB7E187446A32FB5BD730F7` | `8DAD74412099CE0B31D6FAC2EF17F755854F69E6` | `700D18669BE2AABA61F2218707C47ED8` |

## Метадані

- **Ім'я файлу:** `TeeDriverW8_6.sys`
- **Розмір:** 192456 bytes
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
