# `PRI-Driver.sys`

[Назад до індексу](../README.uk.md) · [English version](PRI-Driver.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `FEA19D478F7FE6DC5109ABA767C1B952F389159E98456BB0046F785AB3FF476C` | `CF82BCE42ACD57A7F8FF1FB1C3962D7D35352C39` | `0E6B8871764BAAF082B36C4BF101B869` |

## Метадані

- **Ім'я файлу:** `PRI-Driver.sys`
- **Розмір:** 378000 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Platform Register Interface Driver
- **Опис:** Intel(R) Platform Register Interface Driver 
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
