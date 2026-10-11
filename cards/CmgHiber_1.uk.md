# `CmgHiber_1.sys`

[Назад до індексу](../README.uk.md) · [English version](CmgHiber_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8510AF9EB7759DB7F435B6F5DF9D62FCE39CA2C7CDCAEFF5CD37BE314EEEE317` | `5F7D8B9359117F0F3D1CCE63B3DAB88965D4B9DF` | `4E2345D4B374E3834FC67EBD51BF14E5` |

## Метадані

- **Ім'я файлу:** `CmgHiber_1.sys`
- **Розмір:** 149728 bytes
- **Архітектура:** 0x8664
- **Компанія:** Dell Inc.
- **Продукт:** Dell Data Protection Encryption
- **Опис:** CmgHiber Device Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 100

## Профіль можливостей

**Primitives:** `MDL allocation`, `contiguous physical allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmAllocateContiguousMemory`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
