# `devmap.sys`

[Назад до індексу](../README.uk.md) · [English version](devmap.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6062003A59F3B7CE48C8D2899DCDC51847816A5831E15555B6A92C154E55CD2B` | `62F94E42F5BC4BC9BBCE350C2CF5737D3B0CCC5F` | `EAE51D912CBCB6FC328848A2AB9F7951` |

## Метадані

- **Ім'я файлу:** `devmap.sys`
- **Розмір:** 57344 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Device Mapper Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
