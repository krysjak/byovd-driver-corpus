# `NETwtw04_2.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw04_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DC1C03D96D593CF4520D5C24A2330820D674EC5135083D4BEBC8B0FB2DD63B2B` | `8045590DB77C4241A924F25CAD0A28A00AC97872` | `F181E801430187586BD8E1F4A6EA273A` |

## Метадані

- **Ім'я файлу:** `NETwtw04_2.sys`
- **Розмір:** 8762936 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
