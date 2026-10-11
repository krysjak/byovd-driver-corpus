# `amdacpbus_1.sys`

[Назад до індексу](../README.uk.md) · [English version](amdacpbus_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EC136DEECC6BE4FF1A03B7DB7EDEC2E48B4557B878FD034436C48FBD96425A67` | `3A3199D50245F40936AD6882C5BBAD8DAEDDB9C1` | `56B19F3F5E044B5EE50A8A6B673CB15F` |

## Метадані

- **Ім'я файлу:** `amdacpbus_1.sys`
- **Розмір:** 6188472 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices
- **Продукт:** AMD Audio CoProcessor
- **Опис:** AMD Audio CoProcessor
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
