# `volsnap.sys`

[Назад до індексу](../README.uk.md) · [English version](volsnap.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `48F93F83AD24CA500586223CCD8C76B200574F0F9A9AE6100DA60171C87A9CB9` | `EE7596431E66A4CC199D39BC221C755518D93F35` | `8F9CA5327986717A161CBD0EB1ABAA0C` |

## Метадані

- **Ім'я файлу:** `volsnap.sys`
- **Розмір:** 542208 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Volume Shadow Copy driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `section mapping (kernel R/W surface)`

**Imports:** `IoAllocateMdl`, `MmProbeAndLockPages`, `ZwMapViewOfSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
