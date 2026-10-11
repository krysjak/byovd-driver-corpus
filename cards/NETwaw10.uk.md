# `NETwaw10.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwaw10.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0B89F692E74C15585D3E3582A3B1A2064D9597EBBDE8D91B156E20650CA672A2` | `37A835F5D3F8066E125EFF25F58E4026C7707F07` | `F138CB339CEEE2EB456845D2DC07288F` |

## Метадані

- **Ім'я файлу:** `NETwaw10.sys`
- **Розмір:** 5178424 bytes
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
