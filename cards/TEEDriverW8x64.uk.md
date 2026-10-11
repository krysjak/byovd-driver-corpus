# `TEEDriverW8x64.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW8x64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F6A771023198728E88AE1BC521668C7F806B657C79A085CFB640D72D7FDF7ADE` | `7E5668740D22DB2D252825DE986A610AAC7F3677` | `E4E18E0A78FB8E8EA5ACD608BD625C66` |

## Метадані

- **Ім'я файлу:** `TEEDriverW8x64.sys`
- **Розмір:** 277408 bytes
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
