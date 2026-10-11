# `ataport_2.sys`

[Назад до індексу](../README.uk.md) · [English version](ataport_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `F198A94329350CE6FFAE7D1F431799E8EC345EFE2E7C52DF8BDE9C72D2C78116` | `AB8438DB77323BCA83DD0529E4E96C6254F207A7` | `D3922D7786584FF6CD8D00A67606B558` |

## Метадані

- **Ім'я файлу:** `ataport_2.sys` (Ідентичні копії: `ataport_3.sys`)
- **Розмір:** 284032 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** ATAPI Driver Extension
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 140

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
