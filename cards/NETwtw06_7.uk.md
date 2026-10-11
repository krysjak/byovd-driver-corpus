# `NETwtw06_7.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw06_7.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `0F0E3AD25872EBB6F464F5A28E6EEE9415FA5155CC19BDB53D8DE9B868F168E7` | `62993382A0EE4105F850E11E19CD13080565B1B2` | `E1F050351D6A5787D78555A4C24ADF9F` |

## Метадані

- **Ім'я файлу:** `NETwtw06_7.sys`
- **Розмір:** 8822392 bytes
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
