# `iorate.sys`

[Назад до індексу](../README.uk.md) · [English version](iorate.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F35E1F621E1694495EE51306FE950739F3A83CDE80D005476D1E960303EEF53B` | `47AAA90239F39A5FAF77A168FE1D96252617D8D1` | `907123DC3C0F03F961276A3F18EA9254` |

## Метадані

- **Ім'я файлу:** `iorate.sys`
- **Розмір:** 91624 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** I/O rate control Filter
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
