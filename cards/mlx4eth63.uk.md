# `mlx4eth63.sys`

[Назад до індексу](../README.uk.md) · [English version](mlx4eth63.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B2CBDB7E4FBA8C1F59B1FE4AD02FBCE7EF514781FA7FAEF5C368F457E63D1A9F` | `C47E2F07BA31D8AECF74335DE4895934DFF912A1` | `9E3B1BDC7E8B84E5DC2331BA71CBBDDD` |

## Метадані

- **Ім'я файлу:** `mlx4eth63.sys`
- **Розмір:** 709952 bytes
- **Архітектура:** 0x8664
- **Компанія:** Mellanox
- **Продукт:** MLNX_EN
- **Опис:** Mellanox ConnectX 10Gb Ethernet Adapter NDIS 6.60 driver
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
