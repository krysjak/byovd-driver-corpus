# `winhvr.sys`

[Назад до індексу](../README.uk.md) · [English version](winhvr.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7D407FC49711176E3E8F3E4ECF68121AB7031804C9058B3D893ACC92DEECA1CE` | `A5C71E8B8CE66F1220C3C4EF6B28C85B8A8F3B91` | `D53BE6E7188953AE164C4E69EC0163A9` |

## Метадані

- **Ім'я файлу:** `winhvr.sys`
- **Розмір:** 153064 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Windows Hypervisor Root Interface Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`, `system information set`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `ZwSetSystemInformation`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
