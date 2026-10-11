# `TeeDriverGscW8x64_8.sys`

[Назад до індексу](../README.uk.md) · [English version](TeeDriverGscW8x64_8.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `084016B1B2361E95F0F28D72FAE6396280626FFF587BE265E8A4672CD5A12D0D` | `A25D67765266D49389F34118FCB21EB5BB6A9FC5` | `2400C6E2646B2E4311E38A34E6249E85` |

## Метадані

- **Ім'я файлу:** `TeeDriverGscW8x64_8.sys`
- **Розмір:** 262752 bytes
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
