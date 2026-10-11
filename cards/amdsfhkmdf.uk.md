# `amdsfhkmdf.sys`

[Назад до індексу](../README.uk.md) · [English version](amdsfhkmdf.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7BBBB39686512191D3A7F785326CDDC3579F0FF2654228A6AAFCE0E05A2EF86A` | `2634D207C85E54839D1EAD38D371207FDAC854E8` | `2F63A22B5AD963ACF77587A134F5C7A6` |

## Метадані

- **Ім'я файлу:** `amdsfhkmdf.sys`
- **Розмір:** 159936 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc.
- **Продукт:** AMD SFH KMDF
- **Опис:** AMD SFH KMDF
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
