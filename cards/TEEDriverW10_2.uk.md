# `TEEDriverW10_2.sys`

[Назад до індексу](../README.uk.md) · [English version](TEEDriverW10_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `6D9D0EBA3339CB58AFF4B5F255FAB8556DEBB4C8FCDC524C7F50F6A0404B3279` | `4B033674A3E990417B95205CF394D50AA0ED7E49` | `F8FE2E67168859EF1AC9363231A6581F` |

## Метадані

- **Ім'я файлу:** `TEEDriverW10_2.sys`
- **Розмір:** 264736 bytes
- **Архітектура:** 0x14c
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Management Engine Interface
- **Опис:** Intel(R) Management Engine Interface
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
