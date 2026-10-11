# `BCMWL63AL.SYS`

[Назад до індексу](../README.uk.md) · [English version](BCMWL63AL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `388107153B70C3107CE2DB72E319A15EF78A6BE776D155F5ECE9F9A64A3B8814` | `9AFA84F1718E4E144DC3346603898D44B7EDB532` | `34CFED0DFCC0FECF4B5F817D54904E9B` |

## Метадані

- **Ім'я файлу:** `BCMWL63AL.SYS`
- **Розмір:** 5170176 bytes
- **Архітектура:** 0x8664
- **Компанія:** Broadcom Corporation
- **Продукт:** Broadcom 802.11 Network Adapter wireless driver
- **Опис:** Broadcom 802.11 Network Adapter wireless driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
