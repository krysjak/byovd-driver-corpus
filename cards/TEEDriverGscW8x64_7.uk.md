# `TEEDriverGscW8x64_7.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverGscW8x64_7.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EF512B1E2C23A7EC77F41306D3D4D463E8554AF2F2B5D42BAF089F854CDBEA74` | `D40A6B8360A825BFF3E5493821494866E6F0AD0C` | `35D77D727D4DB96019ED3A34B466E5B2` |

## Метадані

- **Ім'я файлу:** `TEEDriverGscW8x64_7.sys`
- **Розмір:** 279232 bytes
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
