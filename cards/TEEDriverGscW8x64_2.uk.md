# `TEEDriverGscW8x64_2.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverGscW8x64_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9ED1CABC8219C2C62436D2606C633D34F75A4B820011E4EB03E3B3AF43F9E35E` | `36D96566794C2620A15E37CB3A18E62084B0DEBB` | `C8732BAB82C30A6945A4DAD8CEF67301` |

## Метадані

- **Ім'я файлу:** `TEEDriverGscW8x64_2.sys`
- **Розмір:** 276384 bytes
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
