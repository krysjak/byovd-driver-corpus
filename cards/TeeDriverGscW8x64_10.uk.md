# `TeeDriverGscW8x64_10.sys`

[Назад до індексу](../README.uk.md) · [English version](TeeDriverGscW8x64_10.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `960EE19FAD14586FD8054352518CD8B09B189E3206FF6AB7DA6AF6FA7EC3B8BC` | `362340483E0331836A59E13703D949D7D75058CF` | `61DC7FA1A1F1DB32AA7B7F0811ACE26E` |

## Метадані

- **Ім'я файлу:** `TeeDriverGscW8x64_10.sys`
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
