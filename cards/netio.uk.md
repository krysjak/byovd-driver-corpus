# `netio.sys`

[Назад до індексу](../README.uk.md) · [English version](netio.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `801CB171DAC254C3C280B8F06C6C0F08236C42F771364E55680B536C964C5B3D` | `2F2364E559E8BBE96598AA4A752E0DF2A55ACADC` | `71AA515E1591C267866BEE4F53F70088` |

## Метадані

- **Ім'я файлу:** `netio.sys`
- **Розмір:** 746992 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Network I/O Subsystem
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `driver loading`

**Imports:** `IoAllocateMdl`, `ZwLoadDriver`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
