# `CtiAIo64.sys`

[Назад до індексу](../README.uk.md) · [English version](CtiAIo64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `90B1422B71BAF1AD713DBF7D5E74B566622DEFF44451F7E69667562D3E221A45` | `4BECA13D2AE4EC99764D46432EF59554569882DC` | `58E831247EF3772F3D7AC0B630B9EB00` |

## Метадані

- **Ім'я файлу:** `CtiAIo64.sys`
- **Розмір:** 39672 bytes
- **Архітектура:** 0x8664
- **Компанія:** Creative Technology Innovation Co., LTd.
- **Продукт:** CtiAIo64 Driver Version 1.1
- **Опис:** CTIA IO driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `ZwMapViewOfSection`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
