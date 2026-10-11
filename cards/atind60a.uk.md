# `atind60a.sys`

[Назад до індексу](../README.uk.md) · [English version](atind60a.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `CEB38E216A6E6263CE1AD9A61B5715F2F59555DCCD4DC15103B6012E00F8A991` | `CEB443ADB2175BDD9551CC3AD9979516C9266377` | `267DFE5D6577A7D148B3C46C4CAB659E` |

## Метадані

- **Ім'я файлу:** `atind60a.sys`
- **Розмір:** 544360 bytes
- **Архітектура:** 0x8664
- **Компанія:** Broadcom Limited
- **Продукт:** Broadcom NetXtreme Gigabit Ethernet Driver
- **Опис:** Broadcom NetXtreme Gigabit Ethernet NDIS6.x Unified Driver.
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 115

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`, `section mapping (kernel R/W surface)`, `section object access`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`, `ZwMapViewOfSection`, `ZwOpenSection`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
