# `vmswitch.sys`

[Назад до індексу](../README.uk.md) · [English version](vmswitch.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `EBDADFDD063845195F08619FE987105D119A29572BACBE441BE374BE0F021FD1` | `6717A93F968BF613A9D505AD6A284CFADE1364B1` | `341C34EA6F70C8F9263A4ACA38E1236E` |

## Метадані

- **Ім'я файлу:** `vmswitch.sys`
- **Розмір:** 2569680 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Microsoft® Network Virtualization Service Provider
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
