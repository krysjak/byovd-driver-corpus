# `NETwtw06_2.sys`

[Назад до індексу](../README.uk.md) · [English version](NETwtw06_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `B70DEF092662497EB69EF0E9A525DCB2D91F3BFD90780D5DF832B193E9729E13` | `821196CE47CC2C90A9E1CF714F0DF891498835DA` | `B86397588E784D7077E09BE6A395864D` |

## Метадані

- **Ім'я файлу:** `NETwtw06_2.sys`
- **Розмір:** 8903248 bytes
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
