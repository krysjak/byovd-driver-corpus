# `HECI_1.sys`

[Назад до індексу](../README.uk.md) · [English version](HECI_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0419A59DB73A908C2ED987BEFDBDDEBA3E96C74AB55A29D5D91AFBF9A2B0AF6B` | `233095064A32D9410D6194C72C29828D181E9C14` | `6FAB8EE0457E9795D93B91405766E674` |

## Метадані

- **Ім'я файлу:** `HECI_1.sys`
- **Розмір:** 56320 bytes
- **Архітектура:** 0x14c
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 80

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
