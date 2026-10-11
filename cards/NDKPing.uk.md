# `NDKPing.sys`

[Назад до індексу](../README.uk.md) · [English version](NDKPing.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B515174A7FC47B0E48DA6E7AB1190978E9FA55FDC9AE2E4A3C0D0B42082DE117` | `0B3E2C19F1C851E43285C0361D8E4A2AD7D8EF52` | `B64B91C41B77FCD873C38F8BDCD2C4A7` |

## Метадані

- **Ім'я файлу:** `NDKPing.sys`
- **Розмір:** 112112 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** RDMA Sample Driver
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
