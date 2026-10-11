# `TeeDriverW8x64_3.sys`

[Назад до індексу](../README.uk.md) · [English version](TeeDriverW8x64_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `5D8AF9775DF9A1C3BA0AF87A042621B0587CA2F36BFCACEDF10F4CDCB0F0A2AB` | `CFE40C6CC011A21E40282F121AA573BBE45587F4` | `0AC256421B38CEF110FD2C6A22421E65` |

## Метадані

- **Ім'я файлу:** `TeeDriverW8x64_3.sys`
- **Розмір:** 205984 bytes
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
