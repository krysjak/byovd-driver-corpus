# `NETwtw06_6.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw06_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D9576367DE1E82AD9FB81C8E3DF6E34497320B4ED3D41F4D8AD8D99BC6C4458A` | `4A3F73454147EBA44231DEE0F5FE3D7DB844656B` | `3EFF7B459E1C7275CC4853C7BEB12098` |

## Метадані

- **Ім'я файлу:** `NETwtw06_6.sys`
- **Розмір:** 8832792 bytes
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
