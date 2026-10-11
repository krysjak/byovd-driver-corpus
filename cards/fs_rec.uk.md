# `fs_rec.sys`

[Назад до індексу](../README.uk.md) · [English version](fs_rec.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `799C95DEC78122055300086193767662A6798B537E21AB2E7B9860BE1E252EA3` | `4C258A7C69D8FC901DB308F849119519B2B18EBD` | `788BAE29776ABEBE05F1EFA3A3F7747A` |

## Метадані

- **Ім'я файлу:** `fs_rec.sys`
- **Розмір:** 71072 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** File System Recognizer Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `driver loading`

**Imports:** `ZwLoadDriver`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
