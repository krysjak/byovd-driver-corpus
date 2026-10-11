# `hvservice.sys`

[Назад до індексу](../README.uk.md) · [English version](hvservice.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DE4919F9AE85B2B127F181EEFDE1A03970AED4B2B88958A05A8101F4E156A23B` | `4355804C20D0AF55FF753C4BE5934C01B9E04EDF` | `C03F0C573A2388A63A37B593C8C8433A` |

## Метадані

- **Ім'я файлу:** `hvservice.sys` (Ідентичні копії: `hvservice_1.sys`)
- **Розмір:** 99808 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Hypervisor Boot Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
