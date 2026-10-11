# `Netwtw02.sys`

[Назад до індексу](../README.uk.md) · [English version](Netwtw02.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `24D33FB3DDD889157C606EEDE21CE943A90C658F1AC7BB596F031AA9409D92B3` | `2AD2E933A2642E5D0FCDCACF1AB9D4AEB1574B26` | `F4D84DDD179F8AE0A10016BDDDB8DAA2` |

## Метадані

- **Ім'я файлу:** `Netwtw02.sys`
- **Розмір:** 6715904 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless WiFi Link Adapter
- **Опис:** Intel® Wireless WiFi Link Driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
