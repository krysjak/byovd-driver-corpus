# `bxvbda.sys`

[Назад до індексу](../README.uk.md) · [English version](bxvbda.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `8FCA12E3ABA77F5A64A54431969EDC8B32E1A8F3F6FC06282120FE003B2BE1B9` | `0CC5AA83F863A0A877B44B7F1D7AC79A284C4586` | `56B18293198BA954762BC0688AB82571` |

## Метадані

- **Ім'я файлу:** `bxvbda.sys` (Ідентичні копії: `bxvbda_1.sys`)
- **Розмір:** 534944 bytes
- **Архітектура:** 0x8664
- **Компанія:** QLogic Corporation
- **Продукт:** QLogic Gigabit Ethernet
- **Опис:** QLogic Gigabit Ethernet VBD
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `MmMapIoSpaceEx`, `ZwMapViewOfSection`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
