# `bcmwl63_2.sys`

[Назад до індексу](../README.uk.md) · [English version](bcmwl63_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `9B18E146F1D8F002137C1E8A000B0A59789837DCBCDC9A28A2F262F9B5496A1D` | `2FB1A2A7562B34F7760D3482B17C6BBBA31F3060` | `55D5954B31946C2139B5F2B4D10749E1` |

## Метадані

- **Ім'я файлу:** `bcmwl63_2.sys`
- **Розмір:** 6748336 bytes
- **Архітектура:** 0x14c
- **Компанія:** Broadcom Corporation
- **Продукт:** Broadcom 802.11 Network Adapter wireless driver
- **Опис:** Broadcom 802.11 Network Adapter wireless driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 75

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
