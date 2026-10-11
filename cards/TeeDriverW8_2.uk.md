# `TeeDriverW8_2.sys`

[Назад до індексу](../README.uk.md) · [English version](TeeDriverW8_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EAD78FEE4054C4508ECFE4A2AFD73BF3B2FB212F215E9128BAC3B72A2BED436F` | `BAA3A157B6B768753C8BAF6D9B13CC1565A6DB64` | `E5AA14C43888A103A8ACE362D45FDC44` |

## Метадані

- **Ім'я файлу:** `TeeDriverW8_2.sys`
- **Розмір:** 177664 bytes
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
