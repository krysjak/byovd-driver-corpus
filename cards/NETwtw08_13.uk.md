# `NETwtw08_13.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw08_13.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B49E5820DE04FF4918A9C7511ED887ABCD2ABF2A2001BA57E5E82552C054EDA1` | `37E14933CF39386DDB9EFE9527FB815149090624` | `CF75BDE25CC440FD0A2A0FCBA2D2A63D` |

## Метадані

- **Ім'я файлу:** `NETwtw08_13.sys`
- **Розмір:** 8964216 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
- **Підпис:** signed
- **Джерело:** `oem:hp`
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
