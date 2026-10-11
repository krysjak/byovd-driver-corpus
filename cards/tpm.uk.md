# `tpm.sys`

[Назад до індексу](../README.uk.md) · [English version](tpm.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `2BEF98B8653C7A2886081680CFBA5D971CE73D350517431E157929A1A83D754F` | `23718ACE2F2CC37C561D5D2503639C43DB518E65` | `19A27C8A57862B42B79A554142AC3DD0` |

## Метадані

- **Ім'я файлу:** `tpm.sys` (Ідентичні копії: `tpm_1.sys`)
- **Розмір:** 374224 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** TPM Device Driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
