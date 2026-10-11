# `hvservice_2.sys`

[Назад до індексу](../README.uk.md) · [English version](hvservice_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C9DF62EF78C6AD89C3200EB60244E5779E86BB8AD15B508024CB18FADFECD10D` | `8BF0EED14A88CDB52F1BF43C39AD472B38FD5B2A` | `5236C3E954FED48C0B0E429F2A0A9AD2` |

## Метадані

- **Ім'я файлу:** `hvservice_2.sys` (Ідентичні копії: `hvservice_3.sys`)
- **Розмір:** 103824 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Hypervisor Boot Driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 75

## Профіль можливостей

**Primitives:** `MDL allocation`, `process address-space attach`

**Imports:** `IoAllocateMdl`, `KeStackAttachProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
