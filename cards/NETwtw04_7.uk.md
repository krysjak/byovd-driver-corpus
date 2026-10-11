# `NETwtw04_7.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw04_7.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `11DDEADCBA88EE12A96B22409D16494D86262D3F315E908756E034484FD14966` | `6FEDE059A17BFB218C03928806BAAC683FB32949` | `8AB86BAB99B5B6CD96EBAB279EB43B72` |

## Метадані

- **Ім'я файлу:** `NETwtw04_7.sys`
- **Розмір:** 8717808 bytes
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
