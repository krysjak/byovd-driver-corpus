# `netadaptercx.sys`

[Назад до індексу](../README.uk.md) · [English version](netadaptercx.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `35E8D4B8BE124840410A69AF486C30600A623E105B6127876518E53B9E8EC19E` | `A673F3D365AF6DAE5B299AC690593B7164BFEEA7` | `B22FD227938A4C383E667FC5B6D9E0EF` |

## Метадані

- **Ім'я файлу:** `netadaptercx.sys`
- **Розмір:** 394752 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Network Adapter Class Extension for WDF
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical address resolution`, `process address-space attach`

**Imports:** `KeStackAttachProcess`, `MmGetPhysicalAddress`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
