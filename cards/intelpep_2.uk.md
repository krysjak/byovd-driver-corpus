# `intelpep_2.sys`

[Назад до індексу](../README.uk.md) · [English version](intelpep_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `865F9566A0F0C5E23C256DB20CEBBF258204940F722391A1B378FA51718418D2` | `110E7C5F1682769F10639A79DC7AC804118F4767` | `910E484459B18A7E81831016B66FD716` |

## Метадані

- **Ім'я файлу:** `intelpep_2.sys` (Ідентичні копії: `intelpep_3.sys`)
- **Розмір:** 641424 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** Intel Power Engine Plugin
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
