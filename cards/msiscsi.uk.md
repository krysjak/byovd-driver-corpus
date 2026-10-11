# `msiscsi.sys`

[Назад до індексу](../README.uk.md) · [English version](msiscsi.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `E8FE743F63E439EE79CA6625B26A4936B719CD61D3FCC67987E06DAE7733CF17` | `A70093428A22769BDEE1DD30B3857B5B330D6A66` | `3295AC755E7A6CA887ED71430826D905` |

## Метадані

- **Ім'я файлу:** `msiscsi.sys` (Ідентичні копії: `msiscsi_1.sys`)
- **Розмір:** 333240 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft iSCSI Initiator Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
