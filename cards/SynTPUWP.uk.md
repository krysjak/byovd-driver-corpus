# `SynTPUWP.sys`

[Назад до індексу](../README.uk.md) · [English version](SynTPUWP.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BA51CDEF49BED797A36ECC5AD41EBCD792B9AB1F86D810350016B5A4C5ADA48C` | `6A3D2F86756EEA65C4EB49092AB7728A7D611162` | `76494BC6DEF95C308CF62EA9311BE774` |

## Метадані

- **Ім'я файлу:** `SynTPUWP.sys`
- **Розмір:** 752984 bytes
- **Архітектура:** 0x8664
- **Компанія:** Synaptics Incorporated
- **Продукт:** Synaptics Pointing Device Driver
- **Опис:** Synaptics Touchpad Win64 Driver
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
