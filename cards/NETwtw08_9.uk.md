# `NETwtw08_9.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw08_9.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `1842F1028A5F5356A090E744A956A6917E8EFF75E10C523BA24244CC8648FE3E` | `697C4A0C58D24431502B4B937BA95C7C135BC18D` | `8E143210A4FE196A62575AE93A5F7B76` |

## Метадані

- **Ім'я файлу:** `NETwtw08_9.sys`
- **Розмір:** 9276192 bytes
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
