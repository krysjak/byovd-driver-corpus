# `AMDPCIDev.sys`

[Назад до індексу](../README.uk.md) · [English version](AMDPCIDev.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `48FDADD0651BE4D5081CC636C0CCDA30C602506F4C02ED58D9A3E46B74C4564D` | `2D0B685A5F6B46E74499DB29D3D5F56144220C39` | `F5B4FC4DBF511C6DB3EAAC710421EB4C` |

## Метадані

- **Ім'я файлу:** `AMDPCIDev.sys`
- **Розмір:** 39048 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices
- **Продукт:** AMD PCI Device driver
- **Опис:** AMD PCI Device driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `process handle access`

**Imports:** `ZwOpenProcess`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
