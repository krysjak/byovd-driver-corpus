# `TeeDriverGscW8x64_4.sys`

[Назад до індексу](../README.uk.md) · [English version](TeeDriverGscW8x64_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1880CB83FF9ECA48D9026250AF75173FCE9A369E9B3048338A174339B33DD1F8` | `1F7C864420350C781CD09F4F8A2B31A4F75D7D64` | `48A5458CB6CA14AF9FBE8486F8E99C70` |

## Метадані

- **Ім'я файлу:** `TeeDriverGscW8x64_4.sys`
- **Розмір:** 258104 bytes
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
