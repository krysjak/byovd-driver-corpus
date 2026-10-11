# `cng.sys`

[Назад до індексу](../README.uk.md) · [English version](cng.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1C6BEE721C0FB2BCBE02F92308828CBF8E9CEFC1EC131198B0F86627CA54D41F` | `5552E1AEF89EC1C66B886DA67FF48A8E970E272A` | `605A5A569CEF7F43A0996A1A484904AC` |

## Метадані

- **Ім'я файлу:** `cng.sys`
- **Розмір:** 964288 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Kernel Cryptography, Next Generation
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `driver loading`, `process lookup`, `system information set`

**Imports:** `PsLookupProcessByProcessId`, `ZwLoadDriver`, `ZwSetSystemInformation`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
