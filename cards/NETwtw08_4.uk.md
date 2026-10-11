# `NETwtw08_4.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw08_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `DA5B6206A66517D6494BB256BCF204242253BA3C1CD829E78C1B02A4EEA69D53` | `31B6EE62EEE9BB8842A2FB7FF4342AA83EEBB144` | `992F74F1FE36C9BF8701808D02EF123C` |

## Метадані

- **Ім'я файлу:** `NETwtw08_4.sys`
- **Розмір:** 8815688 bytes
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
