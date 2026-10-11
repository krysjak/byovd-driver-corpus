# `partmgr.sys`

[Назад до індексу](../README.uk.md) · [English version](partmgr.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `978267BFE7B8967F4A560BF6178FBED7D5953040CDE4EC7A4E69A8C14D2071EC` | `7502D81D07D1289EA71D211ABCCD6B43AEC95CE1` | `5797DD3B622B0A6E113A90F993A522E2` |

## Метадані

- **Ім'я файлу:** `partmgr.sys`
- **Розмір:** 226800 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Partition driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
