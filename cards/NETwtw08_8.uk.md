# `NETwtw08_8.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw08_8.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `AAD79C01E7A45F6646DFF7D5CAE235EB8D4A644C9C8B8808384D3BE463758248` | `65BA75D90B3E297D573C0705BC23DCC25D29D269` | `53D74DB73FF392586D492EF84C5D4E1F` |

## Метадані

- **Ім'я файлу:** `NETwtw08_8.sys`
- **Розмір:** 8818256 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
