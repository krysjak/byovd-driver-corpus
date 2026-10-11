# `dwprot.sys`

[Назад до індексу](../README.uk.md) · [English version](dwprot.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F80AB81552926676E833D8A925303F6602988016241F54B6E496C049407CFE06` | `89F2D99F158A188BCD45964F893C23033EFF5AAC` | `5ACE1DEEF102DF84FC7FAF497D132C98` |

## Метадані

- **Ім'я файлу:** `dwprot.sys`
- **Розмір:** 153880 bytes
- **Архітектура:** 0x8664
- **Компанія:** Doctor Web, Ltd.
- **Продукт:** Dr.Web Anti-Virus
- **Опис:** Dr.Web Protection for Windows
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `process address-space attach`, `process lookup`, `section mapping (kernel R/W surface)`

**Imports:** `KeStackAttachProcess`, `PsLookupProcessByProcessId`, `ZwMapViewOfSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
