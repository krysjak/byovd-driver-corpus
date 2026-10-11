# `NETwtw06_1.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw06_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `32B892577666433B4641B7D048EC96B52AA0752F3CE92CDFD2D8F0E25C7314FB` | `2CA9A84DFC0024995CEDA27E1251D654231ACCE7` | `3553CA8929F723ED63C9AF8AA98989C5` |

## Метадані

- **Ім'я файлу:** `NETwtw06_1.sys`
- **Розмір:** 8809320 bytes
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
