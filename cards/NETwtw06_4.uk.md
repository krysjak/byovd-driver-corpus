# `NETwtw06_4.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw06_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `7D4524466E6D66BC990883ED9D78CB89A9ED50AE4A0583372D142989519A1FF4` | `89725B611FBED0D39381A839C72974859269DA6B` | `FF2256FA6C9A1AA8CA13D768FD09C489` |

## Метадані

- **Ім'я файлу:** `NETwtw06_4.sys`
- **Розмір:** 8831480 bytes
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
