# `ykinx64.sys`

[Назад до індексу](../README.uk.md) · [English version](ykinx64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `823EE97F1EAFA80E3D3692EC5CD79E8F0C7AD8222AC96DA009EBE9F709555BF8` | `DC97D8F78F787A54FC70FCE80612F1854B6DC362` | `E9C0D4DFF1F4E0F4B4534114E2185DCD` |

## Метадані

- **Ім'я файлу:** `ykinx64.sys`
- **Розмір:** 288768 bytes
- **Архітектура:** 0x8664
- **Компанія:** Marvell
- **Продукт:** Marvell Yukon Ethernet Controller
- **Опис:** NDIS6.30 Miniport Driver for Marvell Yukon Ethernet Controller
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `ZwMapViewOfSection`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
