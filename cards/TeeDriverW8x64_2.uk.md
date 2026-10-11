# `TeeDriverW8x64_2.sys`

[Назад до індексу](../README.uk.md) · [English version](TeeDriverW8x64_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5F03180B3F892E57A9748F8987D56B20C4E445AD0DAF4BDF245D65DBC05CC832` | `184A660A1B599841BF34DFD622957A6846F7FC56` | `4A5925A9B4C511CC031B824F5275BE5E` |

## Метадані

- **Ім'я файлу:** `TeeDriverW8x64_2.sys`
- **Розмір:** 204800 bytes
- **Архітектура:** 0x8664
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
