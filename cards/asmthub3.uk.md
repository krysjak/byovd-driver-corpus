# `asmthub3.sys`

[Назад до індексу](../README.uk.md) · [English version](asmthub3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C87A5C6C808E1FD7E4ED0AF6EE9FF64A70D1D6F9C951966E2A2EA49F41C456D3` | `1B0AC225AAF4E69F5AB679DB4BAA5D6FB352C88B` | `DB5B39DFDE775F792B2E28E7B6B9CD9A` |

## Метадані

- **Ім'я файлу:** `asmthub3.sys`
- **Розмір:** 160936 bytes
- **Архітектура:** 0x8664
- **Компанія:** ASMedia Technology Inc
- **Продукт:** ASMedia USB 3.1 Host Drivers
- **Опис:** ASMedia USB3 Hub Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `MDL allocation`

**Imports:** `IoAllocateMdl`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
