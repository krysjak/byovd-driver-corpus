# `spaceport.sys`

[Назад до індексу](../README.uk.md) · [English version](spaceport.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `76F885B1FF347958E0EF009A0D1FAE5F532DC15BA8119A5F61051180D4161B8D` | `1E3F841AF90644F54F2DB1C21AE450C953C77AE5` | `99588262F38CEFBAE01E3D617B3A420E` |

## Метадані

- **Ім'я файлу:** `spaceport.sys` (Ідентичні копії: `spaceport_2.sys`)
- **Розмір:** 1021416 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Storage Spaces Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
