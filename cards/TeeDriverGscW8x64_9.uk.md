# `TeeDriverGscW8x64_9.sys`

[Назад до індексу](../README.uk.md) · [English version](TeeDriverGscW8x64_9.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `81C0E9C1DAEBF845AB530338D2CDF5C8905F25DF16873CE3C8DC5C280D12C693` | `C673684C5B8F9649131A01BEBC7A7B2EF5D88CA0` | `91B6652FFEFCAF8CDB988C3D37FE095E` |

## Метадані

- **Ім'я файлу:** `TeeDriverGscW8x64_9.sys`
- **Розмір:** 258128 bytes
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
